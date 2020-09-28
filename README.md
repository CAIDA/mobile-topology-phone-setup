# mobile-topology-phone-setup
## Instructions for setting up the phone
### Connect the phone to your computer
- First of all connect the phone to your laptop through USB cable. There should be a permission alert show up on the phone. If not, please open up the [Settings]. Scroll down to the bottom, go to [Developer options] section. Turn off and turn on the [USB debugging] buttons, the permission alert should show up. Give the permission to the computer.
### Open your teminal:
- If you are using Mac OS or Linux: Use `adb devices` to make sure the phone has already connected to your laptop. Then type `adb tcpip 5555`. The experiment should restart.
- If you are using Windows: Get to the dir where you downloaded the adb. Use `./adb devices` to check the connection of the phone. Then type `./adb tcpip 5555`. The experiment should restart.
### If you don't have adb on your computer:
- For Windows: Download the ZIP file from here. https://dl.google.com/android/repository/platform-tools-latest-windows.zip
- For Mac OS: `brew cask install android-platform-tools`
- For Linux: `sudo apt-get install android-tools-adb`
