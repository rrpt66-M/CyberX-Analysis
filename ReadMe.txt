Caution: Do not run the service.exe file when the main program is not running. The file is designed to be used with the main program at the same time. If you run this file when the main program is not running, an error will occur. We will fix it later.
However, if you have already closed the main program, please go to taskmanger or cmd to close service.exe.

This process uses your CPU all the time.
You should close it.


cmd example:

TASKKILL /F /IM service.exe /T
