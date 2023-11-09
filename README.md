# Security-tools
All helpful tools for defensive security


# Moneta

Moneta is a live usermode memory analysis tool for Windows with the capability to detect malware IOCs

If there is something susupicious running in memory you can use this to check what the file is by entering the Process ID.

Github Page: https://github.com/forrest-orr/moneta

Example:

``` Moneta64.exe -m ioc -p 12345 ```

Explain the command:

``` Moneta64.exe``` Runs Moneta 

```-m ioc``` Uses the -m (memory) flag with ioc as the argument (Select only regions which have suspicions associated with them - IOC Specifically stands for Indicators of Compromise.)
    
```-p 12345``` uses the -p flag to denote Process, then specifies 12345 (the process) as the argument.

# Process Hacker

A free, powerful, multi-purpose tool that helps you monitor system resources, debug software and detect malware (A mirror of Process Explorer)

Perfect to use in unison with Moneta, scroll through the processes if you see something suspicious copy the PID and run it through Moneta.

Github Page: https://github.com/PKRoma/ProcessHacker
