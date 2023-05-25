# NASVI (Navigation Assistance for the Visually Impaired)
NASVI is a type of intelligent cane for blind people and is a tool for orientation and mobility for the user. Unlike other common canes, NASVI has different electronic components including sensors, actuators, headphone connection and a camera to fulfill the task of detecting and avoiding obstacles as well as people in the user's environment.

## Artificla_Vision-Mitnicks repository



## Motivation



## Technologies used

*   Raspberry Pi 4

*   Tiva C Series TM4C1294 Connected LaunchPad

* llenar

## Most important functionalities

The device focuses on obstacle, person and vehicle detection, localization and monitoring of the user's location, and real-time guidance via voice audios.

The device has two principal sections of obstacle detection:
* Short distance: Obstacle detection is performed at short distances by means of an infrared distance sensor called Sharp, with a range of no more than 80 centimeters. This is a case in which the user can quickly find out whether or not he is about to collide with a nearby object.

* Long Distance: In this case, use is made of an ultrasonic type sensor which has a greater range with respect to the Sharp sensor, this to detect possible obstacles in an analogical way, this accompanied by the artificial vision model which detects vehicles, traffic lights and people and allows to generate a path for the user to move.

Another main function of the device is the geolocation and monitoring of the user by an external person. The device has sensors in the handle to detect if the user is using the device, so that if a situation arises in which the user suddenly drops the device, another person can be notified of the location of the device at the moment in which the user suddenly released the baton.

Finally, the real-time guidance function, which mainly takes advantage of the processing performed by the artificial vision model and uses video processing functions to detect the sidewalk and thus together generate a route for the user. Depending on the route generated, the user would be guided by voice since the device has the input to connect headphones or wireless bluetooth connection, then different audios would be played to indicate the movements to be made by the user.

## Credits