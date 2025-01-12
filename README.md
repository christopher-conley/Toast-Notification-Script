[README.md](https://raw.githubusercontent.com/imabdk/Toast-Notification-Script/6c54ca160089e489444a0b8aeb382acc1fc68f5e/README.md) from the [original repo](https://github.com/imabdk/Toast-Notification-Script) as it existed on 2025-01-11 is as follows:

___

# Toast Notification Script

## Current version: 2.3.0

Download the complete Windows 11 Toast Notification Script: https://github.com/imabdk/Toast-Notification-Script/blob/master/ToastNotificationScript2.3.0.zip

Blog posts, documentation as well as if any questions, please use: https://www.imab.dk/windows-10-toast-notification-script/

## What's New

- 2.3.0 – Added the Register-CustomNotificationApp function
   - This function retrieves the value of the CustomNotificationApp option from the config.xml
      - The function then uses this name, to create a custom app for doing the notification
      - This will reflect in the shown toast notification, instead of Software Center or PowerShell
   - This also creates the custom notifcation app with a prevention from disabling the toast notifications via the UI
