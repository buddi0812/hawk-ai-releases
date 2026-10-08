# Hawk-AI — releases

Hawk-AI by Defect Scanner turns one industrial PC into an on-prem visual inspection box for factory lines:
it watches the station cameras, checks every work cycle against the SOP, flags missed steps and defects, and alerts
the right people. Video and data never leave the plant.

This repository only hosts **signed release packages**. The source code is private.

## Install

- **USB stick (recommended for plants):** on an office PC with fast internet, PowerShell as Administrator:

  ```powershell
  [Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12; irm https://github.com/buddi0812/hawk-ai-releases/releases/latest/download/make-usb.ps1 | iex
  ```

  Then plug the stick into the box and double-click **Hawk-AI Setup**.
- **Update an installed box:** open the dashboard → System → Updates. For a box on 0.4.2 or older, unzip
  `hawk-update-<version>.zip` on the box and double-click **Apply Hawk-AI update**.

Every package is signed by Defect Scanner; the box refuses anything else.

Support: +91 94455 05499 · hello@defectscanner.com · © Defect Scanner. All rights reserved.
