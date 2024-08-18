<div align="center">
    <img src="https://gegenlicht.net/wortmarke/">
    <h1>Stage Remote Control</h1>
    <p>📡 remote control software allowing interfacing via gpio pins and UDP for mobile remote access</p>
<img alt="License" src="https://img.shields.io/github/license/unikino-gegenlicht/stage-control?style=for-the-badge">

<img alt="Release" src="https://img.shields.io/github/v/release/unikino-gegenlicht/stage-control?sort=semver&display_name=tag&style=for-the-badge">

</div>

> [!IMPORTANT]
> This software is only compatible with our stage and equipment as the
> setup of each cinema is different.

This repository contains the source code for the stage (remote) control 
software.
It enables us to control the lightning and projector screen via a computer
while allowing remote access to the controls using UDP.
Furthermore, it allows controlling other software running on a PC using DBus or
keyboard shortcuts.
While some applications may receive a direct implementation using one of the
aforementioned control mechanics, other applications may be added using the
configuration files.

## Features
> [!NOTE]
> This feature list is updated with every release and may change in future
> as features are added or removed

- [ ] Light Control
  - [ ] Tuya Smart Dimmers
  - [ ] Tuya Smart Switches
- [ ] Projector Screen Control
  - [ ] Calibration of Shelly Device
  - [ ] Movement Up and Down
    - [ ] Automated (based on configuration)
    - [ ] Manual
- [ ] Software Control
  - [ ] SMPlayer
  - [ ] Screen Monkey
- [ ] Hardware Control
  - [ ] Sound Control