# XIAOMI-TOOL-MiFlash-for-Linux-by-IceMan

1- Restart the device in fastboot mode;
2- Connect the device to the PC via USB cable;
3- Start the "XIAOMI TOOL" program from the terminal (cd Xiaomi_MiFlash && sudo ./go.sh) and copy the file
    of the .tgz firmware inside the "/Xiaomi_MiFlash/XIAOMI-FILE/" folder;
4- Type "1" to start FLASH FIRMWARE and at the end of the operation press any key;
5- Select the .sh file and wait for the end of the operation.

Information files .sh:
flash_all.sh : Wipes everything
flash_all_except_storage.sh : Wipes everything except internal storage
flash_all_except_data_storage.sh : wipes everything except apps data and storage

Backup firmware:
1- Restart the device in TWRP mode;
2- Type "2" to start backup and end operations by pressing any key;
