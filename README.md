# FRC Vendor Libraries

![FRC 2023 Season](https://img.shields.io/badge/FRC-2023-blue?logo=FIRST&labelColor=red&logoColor=white)

This is a list of common FRC Vendor libraries and their URLs for easy addition to a project.

Additional offical libraries can be found [here](https://docs.wpilib.org/en/stable/docs/software/wpilib-overview/3rd-party-libraries.html).

[How to add libraries?](#how-to-add-libraries)

| Vendor              | Filename               | URL                                                                                                     | API Docs |
| ------------------- | ---------------------- | ------------------------------------------------------------------------------------------------------- | -------- |
| CTRE Pheonix        | Pheonix.json           | https://maven.ctr-electronics.com/release/com/ctre/phoenix/Phoenix5-frc2023-latest.json                 | https://store.ctr-electronics.com/content/api/java/html/hierarchy.html |
| REV Robotics Lib    | REVLib.json            | https://software-metadata.revrobotics.com/REVLib-2023.json                                              | https://codedocs.revrobotics.com/java/com/revrobotics/package-summary.html |
| KauaiLabs navX      | navx_frc.json          | https://www.kauailabs.com/dist/frc/2022/navx_frc.json                                                   | https://www.kauailabs.com/public_files/navx-mxp/apidocs/java/com/kauailabs/navx/frc/AHRS.html |
| WPILib New Commands | WPILibNewCommands.json | https://raw.githubusercontent.com/wpilibsuite/allwpilib/main/wpilibNewCommands/WPILibNewCommands.json   | |

# How to add libraries

To add a library, first copy the URL of the library you want to add.

Then, in your vscode robot project, press **Ctrl+Shift+P** and begin typing `wpi vendor lib` and select `WPILib: Manage Vendor Libraries`.

Select the option `Install new libraries (online)`, paste the URL you copied, and press enter.
