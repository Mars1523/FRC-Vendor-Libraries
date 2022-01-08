# FRC Vendor Libraries

![FRC 2022 Season](https://img.shields.io/badge/FRC-2022-blue?logo=FIRST&labelColor=black&logoColor=white)

This is a list of common FRC Vendor libraries and their URLs for easy addition to a project.

Additional offical libraries can be found [here](https://docs.wpilib.org/en/stable/docs/software/wpilib-overview/3rd-party-libraries.html).

[How to add libraries?](#how-to-add-libraries)

| Vendor              | Filename               | URL                                                                                                     |
| ------------------- | ---------------------- | ------------------------------------------------------------------------------------------------------- |
| CTRE Pheonix        | Pheonix.json           | https://maven.ctr-electronics.com/release/com/ctre/phoenix/Phoenix-latest.json                          |
| REV Robotics        | REVRobotics.json       | https://software-metadata.revrobotics.com/REVLib.json                                                   |
| REV Color Sensor    | REVColorSensorV3.json  | http://www.revrobotics.com/content/sw/color-sensor-v3/sdk/REVColorSensorV3.json                         |
| KauaiLabs navX      | navx_frc.json          | https://www.kauailabs.com/dist/frc/2022/navx_frc.json                                                   |
| WPILib New Commands | WPILibNewCommands.json | https://raw.githubusercontent.com/wpilibsuite/allwpilib/main/wpilibNewCommands/WPILibNewCommands.json   |

# How to add libraries

To add a library, first copy the URL of the library you want to add.

Then, in your vscode robot project, press **Ctrl+Shift+P** and begin typing `wpi vendor lib` and select `WPILib: Manage Vendor Libraries`.

Select the option `Install new libraries (online)`, paste the URL you copied, and press enter.
