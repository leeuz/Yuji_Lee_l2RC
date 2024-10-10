# Preseason Digital Notebook Example
Name: **[Yuji Lee]**

Section: **[I2RC]**

Week: **[5]**


## Code

The main topic this week was: **[Encoder Drive]**

Commands: **[EncoderDrive]**

Subsystems: **[Drivetrain]**

### How does the code work?
Write about how it works here
**[The code defines a Drivetrain subsystem to control a robot's movement using two motors (left and right) and a gyroscope. Two WL_TalonSRX objects control the motors with ports configured from Constants.DriveTrainPorts, and both motors are set to NeutralMode.Coast, allowing free movement when no voltage is applied. It is also includes a Command called EncoderDrive, which drives the robot based on encoder readings. The constructor takes a Drivetrain object and a setPoint specifying the target distance. The isFinished method checks if the robot has trabeled hthe set distance, ending the command when it is reached.]**


### Important notes for future reference
Notes about git, and helpful resources, etc. 

Please put them here, they will really help you in the future 