# electron_to_uwp_example

## Requirements
- have Windows 10 SDK Installed
- know the path to makecert.exe
- have a compiled electron x64 binary somewhere
- Install node.js 4+ (tested with 14)
- install electron-windows-store

## Steps to execute
- start electron-windows-store
- choose published/cert or let it create a new dev cert
- supply path to built electron app
- supply path to Windows 10 SDK (makecert.exe) location. (e.g.: C:\Program Files (x86)\Windows Kits\10\bin\10.0.18362.0\x64)
- supply name of your exe file of the electron app (it can only consist of letters and numbers, no dashes/underline)
- wait a bit