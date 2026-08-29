For me the original EXE worked + executing this as admin in the Console:

reg add "HKLM\SOFTWARE\Wow6432Node\Oculus VR, LLC\Oculus\Config" /v PreventDashLaunch /t REG_DWORD /d 1 /f
