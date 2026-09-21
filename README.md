# Automatic control system of a cone crusher

This is a demonstration project for the automatic control system of a cone crusher(mining). This repo contains project backup and all exported source files in ConeCrusherWorkspace folder.

## Requirements

- Windows 10 or Windows 11.
- TIA Portal V21 or above.
- Step 7 Professional or above.
- WinCC Unified V21 or above.
- S7-PLCSIM V21 or above.

## Deployment

***Security features are disabled intentionally to make launching the project easier.***

- Retrieve the project in TIA Portal.
- Click on PLC in project tree.
- Click "Start simulation" button.
- Download project into PLCSIM.
- Click on SCADA in project tree.
- Set computer name in device settings to your computer name.
- Complete computer initial setup in WinCC Unified Configuration app, if you haven't done it before.
- Click "Start simulation" button.

## User manual

By default system in simulation mode. Select pumps by clicking on corresponding checkboxes, start lubrication system by pressing Start LuS button, wait until state changes to running. Now crusher is ready to start, click Start crusher button. Oil tank, crusher, all sensors and motors are clickable and contain additional information, controls and settings. To change simulation config press Crusher simulation config button.
