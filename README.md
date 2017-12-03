# XIAOMI-TOOL-MiFlash-for-Linux-by-IceMan

FLASH Firmware:
1- Restart the device in fastboot mode;
2- Connect the device to the PC via USB cable;
3- Start the "XIAOMI TOOL" program from the terminal (cd Xiaomi_MiFlash && sudo ./go.sh) and copy the file
   of the .tgz or .zip firmware inside the "/Xiaomi_MiFlash/XIAOMI-FILE/" folder;
4- Type "1" to start "FLASH Firmware";
5- Select the firmware file (tgz or zip) and wait for the end of the operation;
6- Select the affected .sh file. The device will restart automatically.

n.b .: For installing firmware in .zip format will be required within the folder
       "/Xiaomi_MiFlash/XIAOMI-FILE/" the TWRP recovery file in .img format.
       Two files will be generated:
       - flash_rom_zip.sh
       - flash_rom_zip_erase_data.sh
       The first is not formatting the "userdata" (so it is recommended for update installations) and restarts
       the device in TWRP mode.
       The second format the "userdata" (then indicated for total firmware change) and restarts the device
       in normal mode.

Backup firmware:
1- Restart the device in TWRP mode;
2- Type "2" to start backup and end operations by pressing any key;

flash TWRP:
1- Restart the device in fastboot mode;
2- Connect the device to the PC via USB cable;
3- Start the "XIAOMI TOOL" program from the terminal (cd Xiaomi_MiFlash && sudo ./go.sh) and copy the file
   of the twrp recovery (.img) inside the "/Xiaomi_MiFlash/XIAOMI-FILE/" folder;
4- Type "3" to start "TWRP flash";
5- Select the recovery file for twrp (.img);
6- The device will automatically restart in TWRP mode.

flash boot.img:
1- Restart the device in fastboot mode;
2- Connect the device to the PC via USB cable;
3- Start the "XIAOMI TOOL" program from the terminal (cd Xiaomi_MiFlash && sudo ./go.sh) and copy the file
   boot.img inside the "/Xiaomi_MiFlash/XIAOMI-FILE/" folder;
4- Type "4" to start "flash boot.img";
5- Select the boot.img file);
6- The device will restart automatically in normal mode.
