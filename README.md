# Windows 10 Enterprise LTSC Remove Evaluation
The script intended to help the people convert Windows 10 Enterprise LTSC Evaluation to Windows 10 Enterprise LTSC who has a genuine Windows 10 Enterprise LTSC product key.

## Disclaimer
1. The product key within the script is came from [Microsoft](https://docs.microsoft.com/en-us/windows-server/get-started/kms-client-activation-keys).
3. A part of resources in the repo are collected from the Internet.
2. The script *is not* a one-click activation or a crack tool that intended to create or activate illegal copies.
4. The script *will clear* all the product key registration information on Windows, including the original product key and KMS server configuration.
5. The script comes with *no warranty*, use it at your own risk.

## Instruction
1. Make sure you are using Windows 10 Enterprise LTSC Evaluation by open `cmd` or `powershell` and run `systeminfo | findstr Windows`.
2. Make sure you close all the applications before you run the script.
3. Make sure the `loader.bat` and `skus.zip` are in the same folder.
4. Run the `loader.bat` and accept for giving Administrator rights. After that, the PC will be restarted immediately.
5. Open `cmd` or `powershell` and run `systeminfo | findstr Windows` to see if the OS name is changed.
6. Activate the system by using the information, including but not limit to the KMS server IP and product key provided by your organization.

## Notes
1. Only tested in Windows Windows 10 Enterprise LTSC Evaluation 21H2 (10.0.19044 Build 19044).
