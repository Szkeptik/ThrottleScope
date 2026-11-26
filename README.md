# ThrottleScope

A free CPU stability and throttle monitor for Windows, made for overclocking and Curve Optimizer undervolting.

**Website and documentation: [throttlescope.com](https://throttlescope.com)**

This repository hosts the ThrottleScope downloads. Get the latest installer from [Releases](https://github.com/Szkeptik/ThrottleScope/releases/latest).

## Installing
1. Download `ThrottleScope-<version>-setup.exe` from the latest release.
2. Run it and accept the administrator prompt. Setup installs ThrottleScope (with .NET included) and, if it's missing, the PawnIO driver it uses to read the CPU's sensors.

Windows SmartScreen may warn that the publisher is unknown, because the installer isn't code-signed yet: choose **More info → Run anyway**.

To remove ThrottleScope, use **Settings → Apps**.

## Third-party software
ThrottleScope uses LibreHardwareMonitorLib (MPL 2.0, [source](https://github.com/LibreHardwareMonitor/LibreHardwareMonitor)), ScottPlot (MIT) and .NET (MIT). The setup includes the unmodified, signed installer of the [PawnIO](https://github.com/namazso/PawnIO) driver (GPL 2.0, [source](https://github.com/namazso/PawnIO)), a separate program that can be removed on its own. Full notices are installed with the program as `THIRD-PARTY-NOTICES.txt`.

© 2026 Dr. Ákos Hornung
