# Security-tools
A repository with lots of important tools, helpful in the security side of things.

# NOTICE
There are little to no tools in this repository as I am currently studying and I don't have time to work on this much.

# Disclaimer 

I do not own any of these tools I just put them in a repository and have tried to keep them up to date as possible, please go and support the creators of each of the tools that you use from this repository.

If you want your tool removed please create an issue and ask me to remove it, I will still give the link to your repository in this readme file - It's really just a convenience thing for most people to have it all added, might not be, create a issue and let me know!

# Moneta

Moneta is a live usermode memory analysis tool for Windows with the capability to detect malware IOCs

If there is something suspicious running in memory you can use this to check what the file is by entering the Process ID.

Github Page: https://github.com/forrest-orr/moneta

Example:

``` Moneta64.exe -m ioc -p 12345 ```

Explain the command:

``` Moneta64.exe``` Runs Moneta 

```-m ioc``` Uses the -m (memory) flag with ioc as the argument (Select only regions which have suspicions associated with them - IOC Specifically stands for Indicators of Compromise.)
    
```-p 12345``` uses the -p flag to denote Process, then specifies 12345 (the process) as the argument.

