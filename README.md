#ArduCAM NOIR Raspberry Pi camera with Motorized IR Cut Filter


Edit config.txt
sudo nano /boot/config.txt

Add this line at the end of the config.txt file, save and reboot.

disable_camera_led=1


Then use our provide python script to take normal image with IR-cut on and night vision image with IR-cut off. Using the following commands there are two pictures captured.

cd piCamLed

sudo python ./RPI_camera_IR_CUT_NOIR.py

sudo python ./RPI_camera_IR_CUT_IR.py

