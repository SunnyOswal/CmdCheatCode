Launch command prompt (as administrator) and run the below command.

User should have administrator permissions on the server.

           SHUTDOWN /r /f /t 0 /m \\<ServerName> /c "<Description>"
/r         Shutdown and restart the computer.

/f         Force running applications to close without forewarning users.

/t xxx     Set the time-out period before shutdown to xxx seconds.

           The valid range is 0-600, with a default of 30.

/m \\computer Specify the target computer.

/c "comment" Comment on the reason for the restart or shutdown.

If there aren’t any issues the system will be restarted
