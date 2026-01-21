# PowerShell Logging & EncodedCommand Detection (Windows)

## Overview
This project demonstrates how PowerShell activity can be logged and analyzed using native Windows telemetry. The lab focuses on identifying and validating PowerShell execution, including encoded commands, by correlating command execution with Windows Event Viewer logs. The goal is to apply SOC style investigation techniques using built in Windows tools.

## Objectives
- Verify PowerShell Operational logging is enabled
- Establish a baseline system timestamp for event correlation
- Execute PowerShell commands, including encoded commands
- Identify and analyze PowerShell events in Event Viewer
- Document findings with labeled evidence

## Environment
- Host System: macOS
- Virtualization: VMware Fusion
- Guest OS: Windows 11 x64
- Tools Used: Windows PowerShell (Administrator), Event Viewer

## Project Structure
```text
powershell-logging-lab/
│── README.md
│── screenshots/
│   ├── Screenshot_01_PowerShell_Operational_Log.png
│   ├── Screenshot_02_EncodedCommand_Execution.png
│   ├── Screenshot_03_EventIDs_Recorded.png
│   ├── Screenshot_04_Get-Date_Baseline.png
│   ├── Screenshot_05_Operational_PostReboot.png
│   ├── Screenshot_06_EncodedCommand_PostReboot.png
│   ├── Screenshot_07_Events_Generated.png
│   └── Screenshot_08_Event_Details.png
