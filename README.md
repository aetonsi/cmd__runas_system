# cmd__runas_system
Simple Windows cli tool to run a program as the SYSTEM user. Depends on Sysinternals' psexec.exe.

# Usage
Please note: requires elevation (elevates automatically if needed).
```powershell
# runas_system.cmd <application> <...arguments>
.\runas_system.cmd mysystemprogram.exe myarg1 myarg2
# starts mysystemprogram.exe as the SYSTEM user, with the specified arguments
```
