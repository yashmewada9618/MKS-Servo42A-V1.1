# MKS-Servo42A-V1.1
Working firmware for Makerbase Servo motor with the board
The firmware folder contains the firmware for the mks motor. Please note this code is working and tested on only MKS SERVO42A V1.1.
#########

**Steps to run and upload this firmware:
1. Download this repo
2. Use this board URL and paste it in your arduino prefrences tab. {https://github.com/Misfittech/arduino-board-index/raw/master/package_misfittech_index.json}
3. Open Arduino>Tools>Board Manager. Type 'Nano' and install the board 'MisfitTech Samd Boards'. pls find the below attached snippets for reference.
4. ![image](https://user-images.githubusercontent.com/54842967/170435101-510d2a27-41b6-4ffc-b933-a93f8b49d9d6.png)

5. Open Arduino>Prefrences and open prefrences.txt at the bottom of the prefrences popup. Goto packages and replace the Misfittech folder with the one in this repo.
6. You also need to install the USB driver for this motor and for this follow this step. {https://github.com/makerbase-mks/MKS-SERVO42A/wiki/MKS-SERVO42A--firmware-build-and-upload-tutorial}. If you are unable to install this driver do install the boards shown in below snippet.![image](https://user-images.githubusercontent.com/54842967/170435594-6cfb6b6b-4281-4514-a04a-81800d9efc33.png)

**The Firmware available {https://github.com/makerbase-mks/MKS-SERVO42A} will not work in some cases. Use the latest firmware in this repo.
Refrences: https://github.com/makerbase-mks/MKS-SERVO42A ,https://github.com/jcchurch13/Mechaduino-Firmware
