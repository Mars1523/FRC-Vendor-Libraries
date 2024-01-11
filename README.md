# FRC Vendor Libraries

![FRC 2023 Season](https://img.shields.io/badge/FRC-2023-blue?logo=FIRST&labelColor=red&logoColor=white)

This is a list of common FRC Vendor libraries and their URLs for easy addition to a project.

[How to add libraries?](#how-to-add-libraries)

| Vendor              | Filename               | URL                                                                                                     | API Docs |
| ------------------- | ---------------------- | ------------------------------------------------------------------------------------------------------- | -------- |
| CTRE Pheonix v5     | Phoenix5-frc2024-latest.json | https://maven.ctr-electronics.com/release/com/ctre/phoenix/Phoenix5-frc2024-latest.json           | https://api.ctr-electronics.com/phoenix/release/java/ |
| CTRE Pheonix v6     | Phoenix6-frc2024-latest.json | https://maven.ctr-electronics.com/release/com/ctre/phoenix6/latest/Phoenix6-frc2024-latest.json   | https://api.ctr-electronics.com/phoenix6/release/java/ |
| REV Robotics Lib    | REVLib.json            | https://software-metadata.revrobotics.com/REVLib-2024.json                                              | https://codedocs.revrobotics.com/java/com/revrobotics/package-summary.html |
| KauaiLabs navX      | NavX.json              |     https://dev.studica.com/releases/2024/NavX.json                                                     | https://www.kauailabs.com/public_files/navx-mxp/apidocs/java/com/kauailabs/navx/frc/AHRS.html |
| WPILib New Commands | WPILibNewCommands.json | https://raw.githubusercontent.com/wpilibsuite/allwpilib/main/wpilibNewCommands/WPILibNewCommands.json   | |

**Note** the [offical WPILib docs](https://docs.wpilib.org/en/stable/docs/software/vscode-overview/3rd-party-libraries.html#libraries) have additional libraries and may be more up to date.


# How to add libraries

To add a library, first copy the URL of the library you want to add.

Then, in your vscode robot project, press **Ctrl+Shift+P** and begin typing `wpi vendor lib` and select `WPILib: Manage Vendor Libraries`.

Select the option `Install new libraries (online)`, paste the URL you copied, and press enter.

[Offical documentation here](https://docs.wpilib.org/en/stable/docs/software/vscode-overview/3rd-party-libraries.html#installing-libraries)
