---
sidebar_position: 2
---

# Mach 3

## Overview

Mach 3 is a Machine Controller software package for Windows. It acts as an interface between the user and the control systems of the mill, allowing you to easily load & run NC code programs from your CAM package, manually contol the mill, or create and run smaller jobs for simple operations. **This page covers the configuration of Mach 3 for this mill.**

**For fine details on Mach 3, please refer to the**
[Mach 3 User Manual.](../../../Datasheets/Mach3Docs/Mach3Mill_Install_Config.pdf)

## Startup config
### Use "Mach 3 Mill" config (Already set as default in shortcuts!)
## Backlash Compensation
### Due to the mill construction, backlash is present.
If carefully measured on each axis, the amount of backlash can be entered into Mach 3

Mach 3 then compensates for the backlash in real time.

This can cause issues on occasion due to the backlash being very inconsistant.

## Mach 3 Config File Backup

[Backup XML for latest Mach 3 config](../../../Mach3Backups/Mach3Mill.xml)

## Mach 3 Installation Backup
[If you really fuck up](../../../Mach3Backups/Mach3.zip)

(can be extracted into C:\ folder.)