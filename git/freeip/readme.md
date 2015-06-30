#Freeip User's Guide

##What freeip is

A Python program designed to find and print a list of free IP Addresses in a given range

##How it works

> Takes a range of IP Addresses using the first and last IP in the range as arguments
    
    Example:
    Find free IPs between 1.0.0.1 and 1.0.0.9:
    
    > python freeip 1.0.0.1 1.0.0.9 
    

> 2. Creates a list of all IP addresses in given range

> 3. Checks all IPs in range for DNS.

> 4. Pings all IPs without DNS to see if they are active.

> 5. Prints a list of all free IPs.
