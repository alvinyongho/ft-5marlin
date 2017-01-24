Remotely flashing onto the octopi:

ssh pi@octop.local
Refer to: http://octoprint.org/download/

pull from this repo

From: https://github.com/guysoft/OctoPi/issues/23#issuecomment-44108934

1. sudo pip install ino
2. sudo apt-get install arduino
3. cd Marlin-Marlin-v1 (to the pulled dir)
4. ln -s Marlin src
5. ino build -m mega2560
6. ino upload -p /dev/ttyACM0 -m mega2560

