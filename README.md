# Security-tools
All helpful tools for defensive security


# Moneta

Moneta is a live usermode memory analysis tool for Windows with the capability to detect malware IOCs

If there is something susupicious running in memory you can use this to check what the file is by entering the Process ID.

Github Page: https://github.com/forrest-orr/moneta

Example:

``` Moneta64.exe -m ioc -p 12345 ```


# Process Hacker

A free, powerful, multi-purpose tool that helps you monitor system resources, debug software and detect malware (A mirror of Process Explorer)

Perfect to use in unison with Moneta, scroll through the processes if you see something suspicious copy the PID and run it through Moneta.

Github Page: https://github.com/PKRoma/ProcessHacker
