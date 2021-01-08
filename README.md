# Office 365 ProPlus, Office 2019, Office 2016 Privacy and Control Enhance
A PowerShell script to automatically configure for some privacy and control settings in Office 365 ProPlus, Office 2019, Office 2016.

## Synopsis
This PowerShell script minimises telemetry and data collection sent to Microsoft and third parties, and optionally, disable online services and first run experiences.

By default, it avoids making changes that remove or disable features or functions, such as PowerPoint Designer and Suggested replies. The script can perform additional optional optimisations with a command line switch. In this mode, it disables online services and first run experience.

The script applies the relevant Group Policies in addition to changing settings. This locks down the setting, and possibly disabling the option in Office Options.

## Usage
Run the PowerShell script file `office-16-enhance-privacy-and-control.ps1` with administrator privileges. This performs the default optimisation where changes are made that do not remove or disable features or functions.

The PowerShell script can be run with the following command line switches:

### Command line switches
- `-OptionalOptimization`: By default, the standard optimisation only changes settings that should not impact any functionality. For example: turning off telemetry data collection, and tightening privacy controls. Optional optimisation goes further by disabling online services and first run experiences.

## Author
Harry Wong (RedAndBlueEraser)
