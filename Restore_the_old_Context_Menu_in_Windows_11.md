Restore the old Context Menu in Windows 11



Open CMD

Paste this and press enter:

reg.exe add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve

Restart File Explorer.
