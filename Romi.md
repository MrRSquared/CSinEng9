The Romi is a mini robot powered by two controllers.

- A Raspberry Pi running this image. This is a single board computer that is a bit slow in IO
- An Arduino 32U4 for instantly controlling the input and output (IO)

The Romi runs regular WPILib programs written in Java, CPP, or Python just like the real robot except, it is through a simulated environment. The robot code Lives and runs on the host computer, not the robot.

WPILib has some excellent documentation. They have many sections.
[Here is a general Overview](https://docs.wpilib.org/en/stable/docs/romi-robot/getting-to-know-romi.html)
[Here is their guide to programming it](https://docs.wpilib.org/en/stable/docs/romi-robot/programming-romi.html)
[Here is thier guide on Supported Hardware (possible Methods)](https://docs.wpilib.org/en/stable/docs/romi-robot/programming-romi.html)
[To change the configuration, you can uise the web interface](https://docs.wpilib.org/en/stable/docs/romi-robot/web-ui.html)

Programming the Romi
- Install the software: start by installing the [WPILib Suite](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/wpilib-setup.html)
- Connect to it: turn on the Romi and connect to it like they do [here](https://docs.wpilib.org/en/stable/docs/romi-robot/imaging-romi.html#wireless-network-setup)
  - You can use the wifi dongle ![wifi dongle](https://i5.walmartimages.com/asr/208ad6ea-8f27-422e-9018-a1c5fcd99cd6.7644846f1bea4d1b4966186b2962a1c5.jpeg?&odnHeight=100)
- Open WPiLib and begin programming.
  - You can start with a new Romi Template, Example, or this blank Skeleton which matches the video.
    Resources:
   - The [WPILib Docs](https://docs.wpilib.org/en/stable/docs/romi-robot/programming-romi.html) are a great place to begin
   - Then, Take a look at [this video series](https://www.youtube.com/watch?v=ihO-mw_4Qpo) from team 6814 Ellipse. [Here](https://github.com/SeanSun6814/FRC0ToAutonomous) is their Git too. It is helpful.
   - If you would like to go deeper into Java Programming, you can look at this video series from the incredible [Team Spectrum Team 3847](https://www.youtube.com/watch?v=j5g4nHV3FaY&t=115s), or
   - Our own [WPILib Course](https://mythinkscape.com/register/3ACACEBE) that goes in depth into how to program the Romi. 

Regardless which robot you choose, here are some challenges for you...

- Make a robot move
- Make it stop after a certain time (Dead Reckoning)
- Make it stop after a specific distance (using an encoder)
- Turn to reach a target angle.
- Use a line sensor <-- You need to borrow additional hardware for this
- Use a rangefinder <-- You need to borrow additional hardware for this
     
