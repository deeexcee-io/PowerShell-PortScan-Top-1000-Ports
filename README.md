# PowerShell-PortScan-Top-1000-Ports
Quick and Easy PowerShell PortScan of the Top 1000 Ports - CSTL Special

Another tool I'm putting together as part of my CSTL Prep.

Quick PowerShell Script to find open ports on a remote network you are pivoting through.

You can either put the script on the box you have popped and run it pointing at the remote network or call it via a UNC Path

## Quick Useage

[+] Setup SMB Share on Kali - impacket-smbserver <share name> <share path> -smb2support

[+] Run from CMD - `powershell.exe -nop -ep bypass -File \\192.168.0.213\share\portscan.ps1`

```
C:\Users\gd\Desktop>powershell.exe -nop -ep bypass -File \\192.168.0.50\gd\PortScan.ps1
Now Scanning 172.16.51.4
22 is Open
25 is Open
80 is Open
```



