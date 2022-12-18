# Connection Listener
Python program that can be set to listen an IP address and port for incoming connections and use that connection to upload or download files

It uses set target IP adress and port to listen for a connection between two systems. You can remotely download or upload files once connection is created.

This Python script works in any UNIX based operating systems and in Windows if Python is installed

Executable works even if Python is not installed

## Usage  (EXE)

```
Syntax: listener.exe [--help] [--ip IP ADDRESS] [--port PORT]

[*] Options:
  -i IP ADDRESS, --ip IP ADDRESS                                 Specify the IP Address to listen to incoming connections
  
  -p PORT, --port PORT                                           Specify the Port used to listen to incoming connections

[*] Example:
  listener.exe -i 0.0.0.0 -p 80                                  Starts listening for connections from IP Address 0.0.0.0 and port 80

```

## Usage  (Python File)

```
Syntax: python listener.py [--help] [--ip IP ADDRESS] [--port PORT]

[*] Options:
  -i IP ADDRESS, --ip IP ADDRESS                                 Specify the IP Address to listen to incoming connections
  
  -p PORT, --port PORT                                           Specify the Port used to listen to incoming connections

[*] Example:
  python listener.py -i 0.0.0.0 -p 80                            Starts listening for connections from IP Address 0.0.0.0 and port 80

```
