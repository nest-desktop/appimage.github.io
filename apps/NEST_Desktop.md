---
layout: app

permalink: /NEST_Desktop/
description: NEST Desktop is a web-based GUI for NEST Simulator and other simulators of spiking networks.

icons:
  - NEST_Desktop/icons/256x256/nest-desktop.png

screenshots:
  - NEST_Desktop/screenshot.png

authors:
  - name: nest-desktop
    url: https://github.com/nest-desktop

links:
  - type: GitHub
    url: nest-desktop/nest-desktop-AppImage
  - type: Download
    url: https://github.com/nest-desktop/nest-desktop-AppImage/releases

desktop:
  Desktop Entry:
    Name: nest-desktop
    Exec: AppRun --no-sandbox %U
    Terminal: false
    Type: Application
    Icon: nest-desktop
    StartupWMClass: nest-desktop
    X-AppImage-Version: 4.0.0
    Comment: NEST Desktop is a web-based application which provides a graphical user
      interface for NEST Simulator.
    Categories: Education
  AppImageHub:
    X-AppImage-Signature: "keybox '/home/runner/.gnupg/pubring.kbx' created [don't
      know]: invalid packet (ctb=0a) no signature found the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line."
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  description: NEST Desktop is a web-based application which provides a graphical user
    interface for NEST Simulator.
  author:
    name: Sebastian Spreizer
    email: spreizer@web.de
  main: dist-electron/main.js
  dependencies: {}
  bugs:
    url: https://github.com/nest-desktop/nest-desktop/issues
  homepage: https://nest-desktop.readthedocs.io
  license: MIT
  repository:
    type: git
    url: https://github.com/nest-desktop/nest-desktop
---
