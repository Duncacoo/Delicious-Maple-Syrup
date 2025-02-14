# FRC Drive Simulator
*This was built in Linux so there may be an issue that arrives. I have not tested*

## Installation
To run the simulator you need to install a few pieces of software.
> [AdvantageScope](https://github.com/Mechanical-Advantage/AdvantageScope/releases/tag/v4.1.2)

> [WPILIB](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/wpilib-setup.html) (Make sure to install everything & install VSCode)

## VSCode
  1. Scroll up and press the dropdown on the `<> Code` button
  2. Copy the URL<sup>1</sup>
  3. Open `FRC VS Code 2025`
  4. Press `Clone Git Repository...`<sup>2</sup>
  5. Paste into the text field & press enter. Find a good spot to put the repository.
  6. Upon opening the cloned repository; if it asks to update it **say no**<sup>3</sup>
  7. Disregard errors until you run a simulation (Press CTRL + Shift + P then type `WPILib: Simulate Robot Code`)
If the build was successful a prompt should open to open Sim GUI, but if it wasn't successful reach out

  ![CopyLocation](https://github.com/user-attachments/assets/28ce9daa-99d8-4dcb-83a5-2170d500cb44)
  
  ![StartOptions](https://github.com/user-attachments/assets/5f950827-1ac6-4835-9343-f96e4ed56d2f)

  ![SAYNO](https://github.com/user-attachments/assets/e0687d88-5334-40a5-94f8-dd4ba71956d3)

## AdvantageScope
  1. Open `AdvantageScope`
  2. File -> Import Layout -> repository folder -> `AdvantageScope Simulation.json`
  3. Connect to Simulator

## Running
It should be connected if you already have the Sim GUI open & AdvantageScope looking for a simulator.
> If it's not connected repeat the final steps in VSCode & AdvantageScope

  1. Plug in your controller & navigate over to Sim GUI; the joystick should be loaded on the left side
  2. Drag the joystick to the first slot at the bottom of the main window by dragging
  3. Switch the mode to `Teleoperated` at the top left of the Sim GUI
  4. Return to `AdvantageScope` and open the `Joysticks` tab
  5. Set the controller in slot 0 to the controller being used
  6. Return to the `3D Field` to see the robot moving when the joysticks are moved

*Do be mindful that it is currently in `Field-Centric` mode*
## Credit
[Original Project](https://github.com/Mechanical-Advantage/AdvantageKit/releases/download/v4.0.0-beta-1/AdvantageKit_TalonFXSwerveTemplate.zip) 
