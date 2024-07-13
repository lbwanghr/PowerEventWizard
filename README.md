# Power Event Wizard
Welcome to the support page for [Power Event Wizard](https://apps.apple.com/cn/app/scheduled-startup-wizard/id6503290654?mt=12).  

Please watch this [video](https://youtu.be/Mh2bkcEp0tE) to learn the usage of this app, and try it on [TestFlight](https://testflight.apple.com/join/XfE2jsU8).

## Introduction
Power Event was once a useful feature provided by MacOS Monterey and earlier systems. However, after upgrading to the latest system, this setting page can no longer be found.

Apple Support suggests you use Terminal to manage this setting. You can learn more from this [link](https://support.apple.com/guide/mac-help/schedule-your-mac-to-turn-on-or-off-mchl40376151/mac).

This app brings the feature back, and provides a page to view the power events set on your mac.

## FAQ

### Why can I only set two events at most? Can I set more?  
This app is based on the native command **pmset**, if you read the manual, you will find there are only two group of events can be set. One contains **wake** and **wakeorpoweron** while another contains **shutdown**, **restart** and **sleep**.  
Only **one** command can take effect in **each** group.

### This app messed up my Login Items page, please help!
You can reset your Login Items page with the following command in Terminal.  
`sfltool resetbtm`


---
You can ask questions in Issues tab or email me directly at lbwanghr@icloud.com.
