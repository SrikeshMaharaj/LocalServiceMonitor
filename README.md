# LocalServiceMonitor

A straight forward, simple script that you can use to monitor a specific service on a remote Windows server and send an email if the service is stopped:

You can schedule this script to run at regular intervals using the Windows Task Scheduler. Simply create a new task, specify the script as the action to be performed, and configure the schedule.

Note: Make sure to replace "Service Name" and "Server Name" with the actual name of the service and the server, respectively. You will also need to configure the Send-MailMessage cmdlet with your email server information.
