# Motion detection
## Introduction

IoT Raspberry Pi motion detection running OpenCV for object detection. The camera will send an email with an image of any objects it detects.

decided to build a motion detection and tracking system using Python and OpenCV. While basic, this system is capable of taking video streams and analyzing them for motion while obtaining fairly reasonable results given the limitations of the method we utilized.

The end goal if this system is to deploy it to a Raspberry Pi, so we did not leverage some of the more advanced background subtraction methods in OpenCV. Instead, we relied on a simple yet reasonably effective assumption

Under this assumption we were able to perform background subtraction, detect motion in our images, and draw a bounding box surrounding the region of the image that contains motion.

## What is it?

The kit is an amazing collection of bits and pieces that allow you to create and customize your very own Motion detection. The kit consists of: -

•	Raspberry pi 3B
•	Raspberry pi camera module
•	Adafruit Raspberry Pi 3B Camera Cable
•	Micro-USB to USB Cable (Generic)
•	Open CV

## How Does it Work?
### Receiving Emails
When receiving an email for the first time, you might get the following notification from Google:

![google](https://user-images.githubusercontent.com/30935981/91423594-5f3f7280-e876-11ea-8089-343c1f679115.jpg)

![per](https://user-images.githubusercontent.com/30935981/91423855-b5acb100-e876-11ea-9289-2adb38df4af2.jpg)

 By default, Google blocks apps from using SMTP without permissions. We can solve this by clicking on the allow "less secure apps" link and toggle the feature on. The next object detected will send an email.
 
 ![abc](https://user-images.githubusercontent.com/30935981/91423985-d96ff700-e876-11ea-8473-8ecfdf207212.jpg)


