# SysDBG

**SysDBG is a Python library for debugging system and receiving information about the system**


**How to use?**

~~~
Pip install Sysdbg
~~~

**Now, lets import it:**

``Import sysdbg``

**Then:**

``From sysdbg import *``


# Functions:

~~~
sysdbg.boottime()
~~~

**This function will give you the time system booted**
**Use it with print() or something else**

~~~
sysdbg.getprocesses()
~~~

**This function Logs the running Processes on the system - PID + File name**

~~~
sysdbg.systeminfo()
~~~

**This function Logs many system information such as:**

**Processer ID**

**CPU Name**

**Number of CPU Cores (Physical and Logical)**

**GPU Model**

**RAM Usage**

**Serial Number**

**Device ID**

**GPU Driver Version**

**IP Address (Private and Public)**

**GPU InfSection**

**GPU ID**

**Total RAM**

**CPU Architecture (Processor)**

**Operating system (Full name with version and service pack)**

**Username**

**HOMEGROUP**

~~~
sysdbg.prefetchget()
~~~

**This function will logs the files first runned date to a file**


# Where files placed?

``All logging files stored in: "C:\\Users\Public"``

**Names: PrefetchLog.txt - Process.txt - System-information.txt**

# Updates

**We making an another update to add more feautres to the Lib**

**If we seen any kind of support version 1.2 will be released for more tools**

**Version: 1.0**

**🌹 Developers: @MehranSpL**

**Made with ❤️ by @MehranSpL**
