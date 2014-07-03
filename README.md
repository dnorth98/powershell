The checkGoogle script is a small powershell script I wrote to test connection to google.  If it fails, connect to my cable modem and pull the stats and event log.

I've scheduled this using Windows task manager to run once a minute

Powershell -file checkGoogle.ps1
