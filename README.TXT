Buffalo is an application to get around Mac Gatekeeper Restrictions.

Macs allow all subprocesses of a signed process to run regardless if they are signed or not. The Java runtime is a signed process, and as such, any unsigned process can be run from it

You can execute the program through BlueJ or another environment. It would be pointless to distribute binaries, as this application is not signed. 

Usage:
      -p - The full path to the executeable
      -a - Any arguments of the executeable

If there are no arguments specified, a window will launch prompting you for values.

NOTE: The path to the executeable is *NOT* the .app folder. The real executeable is usually located further in Contents/MacOS. Right click the app and click "Show Package Contents" to get the full path.

This program is public domain, do whatever you want with it.