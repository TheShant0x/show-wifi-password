# show-wifi-password
Commands to view saved Wi-Fi passwords on Windows.


# Wi-Fi Password Commands (Windows)

## What is this?
This repository stores Windows commands to view saved Wi-Fi passwords.

## Where to Use
Use inside Windows Command Prompt (Admin).

## How to Use
1. Open Command Prompt as Administrator.
2. To see saved Wi-Fi networks:
   netsh wlan show profile
3. To see the password of a specific network:
   netsh wlan show profile name="WiFiName" key=clear

## Notes
- Only works for networks you have connected to before.
- Admin rights are required.
