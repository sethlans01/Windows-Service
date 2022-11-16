# Windows-Service

Add your code in the TODO sections in the code of _service.cpp_.

---

The following commands are meant to be used in a PowerShell instance.

__Install the service:__ ``sc.exe create SERVICE_NAME pathBin="path for the file.exe" start=demand``

__Uninstall the service:__ ``sc.exe delete SERVICE_NAME``

__Find a service:__ ``sc.exe queryex SERVICE_NAME``

__Kill a service:__ ``taskkill /PID SERVICE_PID /F``

_Note: if the start type can also be auto._
