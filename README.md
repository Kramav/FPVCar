# FPVCar
Documentation of the FPV Car 

## Repository Overview


## Parts from amazon

I literally just bought this Amazon kit for the drive train

https://www.amazon.com/DEVIT-ESP32-WROOM-32-Motor-Wheel-Controller/dp/B0BB6RC791

This kit includes an ESP32 WROOM 32 Dev board by DIYMall, 4 basic DC motors and wheel, and an L298N motor controller.

## Software

You will need to install the RemoteXY library for arduino.  Follow the instructions located here. https://remotexy.com/en/library/

An additional copy of the instructions are located in the repository for redundancy.

## Using the ESP32 WROOM 32 and Arduino

Install the esp32 board manager by espreeif.

after installation, use the "ESP32 Dev Module" and set upload type to DIO and upload rate to 115200.

Your set up should look like this:

![image](https://github.com/user-attachments/assets/f997db81-1254-4bc3-9c0c-8af227972ba2)

## Additional Resources

L298N DC Driver Module: (not sure why it does not print to pdf)
https://lastminuteengineers.com/l298n-dc-stepper-driver-arduino-tutorial/#controlling-a-dc-motor

https://www.youtube.com/watch?app=desktop&v=CuZntm0lRIA#:~:text=The%20ESP32%20is%20first%20programmed,button%20switch%20and%20a%20potentiometer.
