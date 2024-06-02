# Scheduled Startup Wizard
Welcome to the support page for Scheduled Startup Wizard.  
There is a demo [video]() to introduce the usage of this app.
You can ask questions in Issues tab or email me directly at lbwanghr@icloud.com.

## Introduction
Scheduled Startup was once a useful feature provided by MacOS Monterey and earlier systems. However, after upgrading to the latest system, this setting page can no longer be found.

Apple Support suggests you use Terminal to manage this setting. You can learn more from this [link](https://support.apple.com/guide/mac-help/schedule-your-mac-to-turn-on-or-off-mchl40376151/mac).

This app provides the terminal command based on your settings, and you just need to paste it into the Terminal and execute it. Then you can return to the main page of this app to view the power events set on your mac.

## FAQ

### Why can I only set two events at most? Can I set more?  
This app is based on the native command **pmset**, if you read the manual, you will find there are only two group of events can be set. One contains **wake** and **wakeorpoweron** and another contains **shutdown**, **restart** and **sleep**.  
Only **one** command can take effect in **each** group.


