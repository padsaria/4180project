# 4180project - Sketches using the Rasberry Pi
# by: William Harrer, Maria Padilla Fuentes, Arianne Perez, Ethan Vargas

The project is a Raspberry Pi Web controlled home security system. It has three parts which are gateway control, user recognition, and Web GUI control. The first part allows user to unlock the door (represented by solenoid) by verifying his fingerprint. User recognition part will send the user a email with snapshot for warning if it detects motion. Web GUI is designed to make user able to get live stream video from multiple Raspberry Pi Cameras, change shooting angles, and even take a picture by clicking a button. If the user finds a invader, he can send different sound alerts to home from the Web GUI.

## Proof I can add a picture
![](blue_pic.png)

## Components
- [Raspberry Pi 3 Model B](https://www.raspberrypi.org/products/raspberry-pi-3-model-b/)
- [Raspberry Pi Camera Module V2](https://www.raspberrypi.org/products/camera-module-v2/)
- [mbed](https://os.mbed.com/platforms/mbed-LPC1768/)
- [Fingerprint Scanner](https://os.mbed.com/users/beanmachine44/notebook/fingerprint-scanner1/)
- [SD Card Reader](https://os.mbed.com/cookbook/SD-Card-File-System)
- [Speaker](https://os.mbed.com/users/4180_1/notebook/using-a-speaker-for-audio-output/)
- [Class D Audio Amp](https://os.mbed.com/users/4180_1/notebook/tpa2005d1-class-d-audio-amp/)

## Pictures
- Fingerprint scanner setup, enrollment, and successful scan
- <img width="250" height="250" src=/images/4.jpg> <img width="250" height="250" src=/images/3.jpg> <img width="250" height="250" src=/images/1.jpg>
- Raspberry Pi Camera setup, mbed connection, and website GUI
- <img width="250" height="250" src=/images/6.jpg> <img width="250" height="250" src=/images/5.jpg> <img width="250" height="250" src=/images/7.jpg>
- Terminal showing website traffic <img src=/images/8.jpg>
- Website Console <img src=/images/9.JPG>

## Demo Video
[![Proof I can make Video/Place Demo Video here](maria_pf_pic)](https://www.youtube.com/watch?v=ybxjrKqWdE4&t=46s)

## Future Work
- Store multiple fingerprints in a SD card
- Website access from outside network using url
- Communications between the three components
