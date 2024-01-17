# MacOsInstall

ISo link https://www.mediafire.com/file/dcji26zay7s3p8r/macOS+Ventura+ISO+for+VM+by+techrechard.com.iso/file




COMMANDs:

cd "C:\Program Files\Oracle\VirtualBox\"

VBoxManage.exe modifyvm "VM NAME" --cpuidset 00000001 000106e5 00100800 0098e3fd bfebfbff

VBoxManage setextradata "VM NAME" "VBoxInternal/Devices/efi/0/Config/DmiSystemProduct" "iMac19,3"

VBoxManage setextradata "VM NAME" "VBoxInternal/Devices/efi/0/Config/DmiSystemVersion" "1.0"

VBoxManage setextradata "VM NAME" "VBoxInternal/Devices/efi/0/Config/DmiBoardProduct" "Iloveapple"

VBoxManage setextradata "VM NAME" "VBoxInternal/Devices/smc/0/Config/DeviceKey" "ourhardworkbythesewordsguardedpleasedontsteal(c)AppleComputerInc"

VBoxManage setextradata "VM NAME" "VBoxInternal/Devices/smc/0/Config/GetKeyFromRealSMC" 1
