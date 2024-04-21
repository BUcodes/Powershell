# Challenge: Up and Down Powershell
The following scenerio was developed by [Iron Scripter](https://ironscripter.us/history/) to access and consolidate scripting skills in Powershell. My solution to the task can be found in the xxxxxx.ps1

## Challenge level: Intermediate
##  Challenge context:
The Chairman has a new challenge to prepare his scripting warriors for the upcoming PowerShell Summit. The Chairman would like a tool that he can use to query a Windows-based server to discover the following information:

- When was a server last shutdown?
- When did the server start up again?
- How long was it down?
- What is the current uptime?

## Expectations
Naturally, the output should include the **computer name** and  **account that initiated the shutdown or reboot**. The function should accept alternate credentials and be able to accept pipeline input for a list of server names.