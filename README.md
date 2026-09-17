## Install Instructions 

The modified printer driver files are too large for me to host here on Github. Here are instructions to create them yourself. Happy printing!

- Download the installer directly from HP [here](https://ftp.hp.com/pub/softlib/software12/HP_Quick_Start/osx/Applications/ASU/HewlettPackardPrinterDrivers.dmg) <br><br>
- Using your terminal, `cd` into the folder where you saved the installer .dmg <br> `cd [path-to-downloaded-files]` <br><br>
- Expand the package <br> 
`pkgutil --expand HewlettPackardPrinterDrivers.pkg drivers`<br><br>
- Using your code editor, remove line 6 "`<installation-check ... />`" from the file `drivers/Distribution`<br><br>
- Save and close the file.<br><br>
- Using your terminal, create the installer <br> `pkgutil --flatten drivers HewlettPackardPrinterDrivers-MacOS-Universal.pkg` <br><br>

- Double click on the created .pkg file to run the installer. 
- Done!<br><br>

----- 
<br/>

## Throw me a bone:
https://www.buymeacoffee.com/interactiverob