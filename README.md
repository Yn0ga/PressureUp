# PressureUp

This is a simple powershell POC for the Steam LPE issue reported by @PsiDragon

Requirements
------------
* Steam client (win32) with at least 1 game installed (otherwise, some registry keys will be missing)

Tested on windows 10 1903.

Warning
-------

This is a POC script which is working on my environment, but your mileage may vary.
Please be aware that this script updates (or at least try to) your registry, instability may occur, please apply responsability and don't deploy on critical system. 


Usage
-----

Just download and run exploit.ps1

By default, the exploit will download and run powercat (https://github.com/besimorhino/powercat) in listening mode (port 6666) under the NT AUTHORITY \ SYSTEM account. 
You can also specify your own payload to download and execute.

Optional arguments
------------------

* PayloadUrl : the url of the payload to be executed
* PayloadExec : payload call + options
* Restore : remove registry modification

Internals
---------

Please refer to https://m.habr.com/ru/company/pm/blog/462479/








