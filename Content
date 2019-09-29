#!/usr/bin/python
import socket 
ip = raw_input("Input a valid IP address: ")
port = input ("Enter port: ")
sock = socket.socket(socket.AF_INET, socket.SOCK_STREAM)
if sock.connect_ex((ip, port)):
        print "Port", port , " is  unavailable!" 
else:
        print "Port", port , "is available"

print "NOTE: SimpleScanner is in early stages, more content will be added, such as a threaded range scanner. The results are accurate though. "

