# SplunkQueries For Powershell Logs
The repo name says it all

## Requirements

This app requires that the following Windows Logs are ingested into Splunk:

* Windows Event Code 4688, 4103 and 4104
* Event Code 4688 MUST log "Include command line in process creation events" in Group Policy

## Setup

All searches within this app are based on the eventtype powershell_index. Change this eventtype either in the UI or the file system ( using a local folder ) to point the searches to the correct area
