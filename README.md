# Convert to Windows 10 Enterprise LTSC
The script intended to help the people convert Windows 10 into **Windows 10 Enterprise LTSC** who have a genuine Windows 10 Enterprise LTSC product key.

## Disclaimer
1. The product key within the script is came from [Microsoft](https://docs.microsoft.com/en-us/windows-server/get-started/kms-client-activation-keys).
3. A part of resources in the repo are collected from the Internet.
2. The script *is not* a one-click activation or a crack tool that intended to create or activate illegal copies.
4. The script *will clear* all the product key registration information on Windows, including the original product key and KMS server configuration.
5. The script comes with *no warranty*, 

## Instruction
1. Make sure you are using Windows 10 Enterprise LTSC Evaluation (i.e., Windows 10) by using command `systeminfo | findstr Windows` on `cmd` or `powershell`.
2. Make sure you close all the applications before you run the script. The PC will be restarted immediately after you run the script.
3. Make sure you have a backup of your system, like system restore point or using whatever software you like to backup your PC. As I mentioned, use it at your own risk.
4. Grab all the file in the repo and make sure `loader.bat` and `skus.zip` are in the same folder.
5. Run `loader.bat` and accept for giving Administrator rights. The script will install a new SKU into the system and restart the PC immediately.
6. Run `systeminfo | findstr Windows` on `cmd` or `powershell` and see if the OS name is changed to Windows 10 Enterprise LTSC.
7. Activate the system by using the information, including but not limit to the KMS server IP and product key provided by your organization.

## Notes
1. Only tested in Windows 10 Enterprise LTSC Evaluation 21H2 (10.0.19044 Build 19044).
