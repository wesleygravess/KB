# 🌉 How To Use The KeepKey Bridge

### **What is the KeepKey Bridge?**

The KeepKey Bridge is a Microsoft Windows application that is designed to help with webUSB connectivity problems between KeepKey and a Windows machine.

The bridge runs as an application that opens a local USB connection to the KeepKey. The bridge exposes a localhost port that the ShapeShift web app can use to communicate with the KeepKey. The KeepKey itself is not aware of the bridge but the ShapeShift web app must be directed to use the bridge.

### **When Should I Try It?**

If you are using a Windows machine and are having trouble getting your KeepKey connected to [**beta.shapeshift.com**](https://beta.shapeshift.com/), try running the bridge by using the instructions below.

### **Installing The Bridge**

**1.** Before using the bridge, be sure that your KeepKey is updated to the most recent bootloader/firmware. The updater app can be found [**here**](https://beta.shapeshift.com/updater-download). Download the latest release of the KeepKey bridge [**here**.](https://github.com/keepkey/python-keepkey/releases)

![kkupdate.png](https://shapeshift.zendesk.com/hc/article\_attachments/4412027362829/kkupdate.png)

_**Note**_: Your computer will likely give some warnings when downloading/running this application. You can click "Run Anyway" to continue the installation.&#x20;

![kkbsetup.png](https://shapeshift.zendesk.com/hc/article\_attachments/4412027356941/kkbsetup.png)

**2.** Once the kkbsetup.exe file is downloaded, you can verify that the file is what we claim it is by comparing the SHA256 of the executable with the published digest in the release notes. This is done by opening up a cmd window (Command Prompt), navigating to the Downloads folder, and typing: **cetuil -hashfile kkbsetup.exe SHA256**. The resulting info displayed should match what is published in the [**python-keepkey releases**](https://github.com/keepkey/python-keepkey/releases) notes. If everything matches up, double click the file to install (_creating a desktop shortcut is recommended for convenience_).

![runanyway.png](https://shapeshift.zendesk.com/hc/article\_attachments/4412021629197/runanyway.png)

### **Using The Bridge**

**3.** When starting the KeepKey Bridge application,  a blank window will appear. Even though it is blank, the bridge is running (we know it's not an ideal UI, but we're working on an improvement soon!). When the window is closed, the bridge will stop running.

![blank.png](https://shapeshift.zendesk.com/hc/article\_attachments/4412027408781/blank.png)

**4.** With the bridge running, head over to [**beta.shapeshift.com**](https://beta.shapeshift.com/). Select KeepKey as the wallet you'd like to pair.

![selectkeepkey.png](https://shapeshift.zendesk.com/hc/article\_attachments/4412030326157/selectkeepkey.png)

![pair1.png](https://shapeshift.zendesk.com/hc/article\_attachments/4412030342285/pair1.png)

**5.** Click the checkbox and then select "TRY KEEPKEY BRIDGE".

![pair2.png](https://shapeshift.zendesk.com/hc/article\_attachments/4412027472909/pair2.png)

![trybridge.png](https://shapeshift.zendesk.com/hc/article\_attachments/4412030346509/trybridge.png)

If successful, your wallet will start syncing and eventually connect to the platform.

![paired.png](https://shapeshift.zendesk.com/hc/article\_attachments/4412030363021/paired.png)

### Troubleshooting

![error.png](https://shapeshift.zendesk.com/hc/article\_attachments/4412030511885/error.png)

If you run into any error messages (like the one pictured above) when attempting to pair your KeepKey via the bridge or it just won't connect, please try the following:

**1.** Go to the [**settings page**](https://beta.shapeshift.com/settings) and "forget" your KeepKey.

**2.** Unplug your KeepKey.

**3.** Refresh [**beta.shapeshift.com**](https://beta.shapeshift.com/).

**4.** Close the bridge application.

**5.** Repeat the steps from the "Using The Bridge" section in this article.
