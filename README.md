The ITC Watch program displays wayside indications in a nicer format than ITCMON.  In the Releases tab you'll find a Windows EXE and an Android APK file (still at v0.5.0).

To install the APK on Android you'll need to enable/allow "installing apk or app from unknown sources" on your phone (will vary how you do this depending on phone and Android version).  It's only been tested on one phone and one tablet so far.

updates since v0.4.0: searches national directory server for public data servers.  first release of android app.

updates since v0.3.0:  added charts, small bug fixes

It gets its data from 'zjpub' servers, so you need to have either ITCMON or IGW running.

It will look for the rrdata.json file and the wius subdirectory in the connected directory the .exe is in.

In addition, if you add milepost numbers to your WIU data, then you can sort the output based on this, for example:

"780207601703": {
  "name": "Oak Ave",
  "MP": 348,
  "sig": "UP",
  ...

The "MP" entry can be an integer or float, or it can be a quoted string with an alphabetic prefix, for example "MP:"CP 42" or "MP":"CPC42"

Click on the Releases link over on the right to download the Windows EXE.
Source code will probably be released after a few updates.

<img width="800" height="350" alt="itcwatch-tn" src="https://github.com/user-attachments/assets/011bb044-7fc3-4419-ba0e-134835baed52" />

<img width="1712" height="1152" alt="itcwatchchart" src="https://github.com/user-attachments/assets/a97f58cc-2b76-4d65-b9cb-4e15e414f5d7" />
