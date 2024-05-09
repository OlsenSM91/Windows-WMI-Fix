# WMI Repair Tool

This is a batch script designed to automate the repair and re-registration of WMI (Windows Management Instrumentation) components to resolve various system issues. It is specifically targeted for systems experiencing WMI-related errors. The script was developed by Steven Olsen and includes functionalities for privilege escalation to ensure it runs with administrator rights.

## Features

- **Automatic Privilege Escalation**: Prompts for administrator rights if not already running with them.
- **WMI Component Repair**: Re-registers crucial WMI DLLs and recompiles MOF files necessary for the correct operation of WMI services.
- **Visual ASCII Art Interface**: Enhances the command-line interface with ASCII art for better visual engagement.

## Prerequisites

- Windows Operating System (Windows 7 or later)
- Batch file execution must be allowed (not blocked by system policies).

## Usage

1. **Download the Batch File**: Click on `WMI_Repair_Tool.bat` to download it.
2. **Run as Administrator**: Right-click the downloaded file and select "Run as administrator".
3. **Follow On-screen Instructions**: The script will guide you through the necessary steps with prompts and messages.

## Important Notes

- This script makes changes to system files and settings crucial for the operation of Windows Management Instrumentation. It is recommended to create a system restore point before running the script.
- The script should be used only if you are experiencing issues with WMI that cannot be resolved through standard troubleshooting steps.

## Disclaimer

This tool is provided "as is," without warranty of any kind. By using this script, you agree that the author is not responsible for any damage caused by the use of this tool. Always ensure you understand what each command in the script does before running it.

## Contributing

Contributions to improve the WMI Repair Tool are welcome. Please feel free to fork the repository, make changes, and submit a pull request.

## Credits

- Script written by: Steven Olsen
- Inspired by an [HP support document](https://support.hpe.com/hpesc/public/docDisplay?docId=c03440207&docLocale=en_US).

## Contact

For support or more information, contact Steven Olsen via GitHub issues.
