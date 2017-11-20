# Some little scripts during the work

1. Cybereason API Client, this client is used for getting data from the Cybereason Cloud Service. The python lib "request" didn't work well, so I used Pycurl instead. And the office API document is not detailed at all, so I have to use the developer mode in Chrome to see what request is sent to the server.
2. Splunk Utils, including a splunk connection wrapper, a result parser, a multi async job executer and two examples for splunk custom command.
3. WMI check script, this is for checking the wmi status for splunk, including installation for wmic and usage of wmi_client_wrapper.