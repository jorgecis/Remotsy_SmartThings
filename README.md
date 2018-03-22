# SmartThings code to use Remotsy
---

## Instalation 


### Using Git Integration
Enabling the GitHub Integration in the IDE is by far the easiest way to install and get the latest updates for Remotsy SmartThings smart app and the device handler.

To enable Git integration (one time configuration) under the IDE please visit here for instructions: IDE GitHub Integration Instructions

**NOTE:** Git Integration is not currently available outside of US and UK


#### Installing The Remotsy connect and the Remotsy control.
First, find the Settings button at the top of SmartThings IDE page (this will only appear after completing the one time integration with GitHub)

![github settings](/readme_imgs/ide_settings.jpg?raw=true "GitHub settings")

Clicking this button will open the GitHub Repository Integration page.
To find the Remotsy SmartThing  code, enter the information below:
**Owner:** jorgecis

**Name:** Remotsy_SmartThings

**Branch:** master

![github params](/readme_imgs/gitss.png?raw=true "GitHub params")

Close the GitHub Repository Integration page
Next, click the Update from Repo button at the upper-right corner of the IDE
Click on Remotsy_SmartThings (master) from the drop down menu
On the right-hand column labelled New (Only in Github), scroll down to click the apps to install. This will typically be:

_remotsy-connect.groovy_

Check the Publish box and Click the Execute Update in the bottom-right corner of the screen. When done syncing, the new apps should now appear in the IDE. If they ever change color, that indicates a new version is available.

**REMINDER!!!: Remember to Enable OAuth under the  Remotsy (Connect) Settings (Instructions Below) **


#### Installing the Remotsy control Device Handlers
Go to "My Device Handlers" in the IDE
Under My Device Handlers Click on Update from Repo and select Remotsy_SmartThings from the drop-down
Check the box next to remotsy-connect then check the Publish box and click Execute Update

That's it in the IDE... Just install "Remotsy Connect" from the Marketplace > MyApps under the mobile app.

When updates are available to the source code the Link color change from black in the IDE.


