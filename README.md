# TinkerTools
* **Open Terminal from**:
 1. Create a bash script and save it in some folder. If you are lazy like me [here’s the gist](https://gist.github.com/rokon-mlbd/1711e874b12f3707a18115367330f059), download and use it:
>  #!/bin/bash
>  
> open -a Terminal "`pwd`"

 2. Make script executable by running this script from Terminal: `chmod +x /path/to/the/open_terminal.sh`
 3. Go to Xcode Preferences. Add a new Behavior by clicking the `+` button in the bottom left corner. Name it and give a shortcut key. In my case `⌘+⌥+⌃+⇧+T`
 ![](ReadMeAssets/Xcode.PNG)
 4. On the right side details pane check the Run option. From the adjacent drop-down menu choose the script you just saved in step 1.

After becoming accustomed to the ease of opening terminal from Xcode, I created two more shortcuts. One to [show project](https://gist.github.com/rokon-mlbd/d552c466999953f96b8e96215ee11ab7) in finder and another one is to open [Derived Data folder](https://gist.github.com/rokon-mlbd/a1382b9015cf7f5401ae93bdd1ac3a0b) from Xcode. The steps are the same as above.


* **Debugging with BurpSuite**

[Burp Suite](https://portswigger.net/burp/communitydownload) allows manual testers to intercept all requests and responses between the browser and the target application, even when HTTPS is being used.

* **DevCleaner**

Xcode could store tens of gigabytes in ~/Developer folder. Most of those cached files & symbols is not reclaimed over time and could consume a large amount of your storage, which is especially important if you have relatively small SSD drive.
[DevCleaner](https://github.com/vashpan/xcode-dev-cleaner) gives you an easy way to inspect auto-generated files and clean them if necessary. It could also remind you about scan after a while.

* **Dropover**

[Dropover](https://dropoverapp.com) is a macOS utility that makes Drag and Drop easier. Use it to stash, gather or move any draggable content without having to open side-by-side windows.

* **Flycut**

[Flycut](https://github.com/TermiT/Flycut) is a clean and simple clipboard manager for developers. It's based on an open source app called Jumpcut. On the Mac, every time you copy a code piece, Flycut stores it in history. Later, you can paste it using Shift-Command-V even if you have something different in your current clipboard. You can change the hotkey and other settings in preferences.

* **Spectacle**

Easily organize windows without using a mouse. [Spectacle](https://github.com/eczarny/spectacle) makes use of several keyboard shortcuts that trigger specific window actions. A window action is nothing more than a command that tells Spectacle how to change the size and/or position of a particular window.

* **Rectangle**

[Rectangle](https://rectangleapp.com) helps you to seemlessly move and resize windows in macOS using keyboard shortcuts or snap areas.

* **ProvisionQL - Quick Look for ipa & provision**

[ProvisionQL](https://github.com/ealeksandrov/ProvisionQL) is inspired by a number of existing alternatives, the goal of this project is to provide clean, reliable, current and open source Quick Look plugin for iOS & macOS developers. Thumbnails will show app icon for .ipa/ .xcarchive or expiring status and device count for .mobileprovision. Quick Look preview will give a lot of information, including devices UUIDs, certificates, entitlements and much more.

* **TinkerTool**

[TinkerTool](https://www.bresink.com/osx/TinkerTool.html) is an application that gives you access to additional preference settings Apple has built into macOS. This allows to activate hidden features in the operating system and in some of the applications delivered with the system.

* **CheatSheet**

Just hold the ⌘-Key a bit longer to get a list of all active short cuts of the current application. It's as simple as that. [CheatSheet](https://www.mediaatelier.com/CheatSheet/) works hand in hand with CustomShortcuts from my friends at Houdah Software. This way, the shortcuts can be edited directly in CustomShortcuts with a click on the pen symbol.

* **ImageOptim**

[ImageOptim](https://imageoptim.com/mac) removes bloated metadata. Saves disk space & bandwidth by compressing images without losing quality.
