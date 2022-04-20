# Activate Microsoft Office 2016
<hr style="border:2px solid gray"> </hr>
Computers running windows 10 and Microsoft Office 2016 (without automatic updates) can intermittently become deactivated due to security issues or operating system incompatibility. In the event this happens and the original license key or email address is unknown follow these instructions.
<hr style="border:2px solid gray"> </hr>

## 1. Open a command prompt as Administrator and type in the following based on your computer specs

### Office 2016 (32-bit) on a 32-bit version of Windows
`cscript.exe "%ProgramFiles%\Microsoft Office\Office16\"ospp.vbs /dstatus`

### Office 2016 (32-bit) on a 64-bit version of Windows
`cscript.exe "C:\Program Files (x86)\Microsoft Office\Office16\OSPP.VBS" /dstatus`

### Office 2016 (64-bit) on a 64-bit version of Windows

`cscript.exe "C:\Program Files\Microsoft Office\Office16\OSPP.VBS" /dstatus`

## 2. Compare license details and attempt to locate the product key. The last 5 characters will be listed on the screen

## 3. If the license key cannot be found
You can use the last 5 characters of the Product Key to remove it using command. Replace <LAST 5 CHARACTERS> with the characters listed on your screen:

### Office 2016 (32-bit) on a 32-bit version of Windows

`cscript "C:\Program Files\Microsoft Office\Office16\OSPP.VBS" /unpkey:<LAST 5 CHARACTERS>`

### Office 2016 (32-bit) on a 64-bit version of Windows

`cscript "C:\Program Files (x86)\Microsoft Office\Office16\OSPP.VBS" /unpkey:<LAST 5 CHARACTERS>`

### Office 2016 (64-bit) on a 64-bit version of Windows

`cscript "C:\Program Files\Microsoft Office\Office16\OSPP.VBS" /unpkey:<LAST 5 CHARACTERS>`

## 4. If you see the following you have successfully removed the exisiting product key 
---------------------------------------
`<Product key uninstall successful>`

## 5. Locate the Microsoft office 2016 Product Key on the CRC Server
## 6. Open a Microsoft Office Application (Word, Outlook, etc)
## 7. Activate using the Product Key

<hr style="border:2px solid gray"> </hr>
If you have any issues following these instructions open an issue or contact [Jordan](https://twitter.com/jordkl).
<hr style="border:2px solid gray"> </hr>



