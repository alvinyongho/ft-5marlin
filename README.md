Remotely flashing onto the octopi:

ssh pi@octop.local
Refer to: http://octoprint.org/download/

pull from this repo

From: https://github.com/guysoft/OctoPi/issues/23#issuecomment-44108934
sudo pip install ino
sudo apt-get install arduino
cd Marlin-Marlin-v1 (to the pulled dir)
ln -s Marlin src
ino build -m mega2560
ino upload -p /dev/ttyACM0 -m mega2560

