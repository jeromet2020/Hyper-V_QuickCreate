# Hyper-V Quick Create Linux

Open regedit.exe

Go to Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Virtualization\

Look for the GalleryLocations. If it doesn't exist, create a new Mult-string value with this name.

If it already exists, set its value to:

```
https://go.microsoft.com/fwlink/?linkid=851584
```
