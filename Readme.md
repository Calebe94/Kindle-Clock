# WebLaunch #

WebLaunch is an extension for the Kindle Touch and Kindle PaperWhite with JailBreak and the application launcher KUAL. It is designed to open a URL without the browser frame to make it look like a native application.
It was designed by PaulFreund in 2013.

This is a version that works on newer generations. Some of the features have been stripped away as I didn't got the time to fix it all. 
You can send pull requests, I'll review it and then accept. I dont have much time for this project anymore.

Battery usage is pretty high. It is a work in progress.

## Important ##

As of this moment there's no way of getting out of the application without restarting the kindle or using USBNetwork to get out of it. Be advised.

## Install ##

* Make sure your Kindle Touch / Kindle PaperWhite is already Jailbreaked
* Make sure you have KUAL installed and the "extensions" folder exists 
* Copy the WebLaunch folder to the "extensions" folder ( don't rename it without changing bin/start.sh first )
* Copy the settings.example.js in the WebLaunch folder to settings.js and change its contents to fit your needs

## Uninstall ##

To remove all traces of WebLaunch call the uninstall.sh script in the bin folder of the extension and delete the WebLaunch folder afterwards. If you changed any installation variables in start.sh make sure you also change them in uninstall.sh before execution.

## Background ##

WebLaunch is based on "mesquite" former WAF and utilizes the "Kindle" template library and a few system librarys based on it to bring as much native browser behaviour as possible.

## Notes ##

Special thanks go to the folks at mobileread.com for their great work opening up the Kindle.
