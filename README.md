# break-a-flask
A simple Flask web app. Register your name and it will say hello to you and it will send email notification to admin that you have registered.

## Environment Variables
Define following environment variables before starting the app:
```
MAIL_SERVER
MAIL_PORT
MAIL_USERNAME
MAIL_PASSWORD
MAIL_SENDER
MAIL_RCPT
```

Example:
```
export MAIL_SERVER=smtp-mail.outlook.com
export MAIL_PORT=587
export MAIL_USERNAME=my-username
export MAIL_PASSWORD=my-password
export MAIL_SENDER=my-username@my-domain.com
export MAIL_RCPT=admin-email-address@domain.com
```
