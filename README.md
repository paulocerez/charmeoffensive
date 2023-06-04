# Charmeoffensive
Simple automated, daily newsletter (probably just quotes and a few ncie words) for your loved ones. &lt;3

# Blueprint 🛠️
- quotes are requested from https://api-ninjas.com/api/quotes via REST HTTP requests
- Python
- smtplib library/module to define an SMTP client session object that can be used to send mail to any internet machine with an SMTP or ESMTP listener daemon (https://docs.python.org/3/library/smtplib.html)
- cron job for automatically timed execution of the script (macOS system, Task Scheduler for other OS)
