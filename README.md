# LBDEventViewerTemplates
Microsoft Dynamics 365 for Finance and Operations Local Business Data Event Viewer Templates for troubleshooting
 
 This contains event viewer views for each node type for an LBD cluster. This is to help streamline node creation as well as troubleshooting when errors occur
 
 To install, find the folder for your node type then import each into Event Viewer or import as follows:

```
eventvwr.exe /v:"Dynamics Log - Last Hour.xml"
eventvwr.exe /v:"Dynamics Log - Last 24 Hours.xml"
eventvwr.exe /v:"Dynamics Errors - Last hour.xml"
eventvwr.exe /v:"Dynamics Errors - Last 24 Hours.xml"
```
