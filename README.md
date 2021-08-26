# COFFEmask Wallet
# Windows & Unix & Chrome Extension

##BUILDER fix

	sudo apt-get install rpm

	#If error build for win replace rcedit.exe
	from https://github.com/electron/node-rcedit/blob/v3.0.1/bin/rcedit.exe
	to node_modules\electron-installer-windows\vendor\squirrel\rcedit.exe

	chmod +x node_modules/7zip-bin/linux/x64/7za

##INSTALLER Unix

sudo snap install --dangerous coffemask-*.*.**.snap