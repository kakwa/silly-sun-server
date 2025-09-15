# My Silly Sun Server

This project gathers the assets I created to put an old Sun V100 to new use.

It contains the following assets:

* 3D models for a custom 10 inches case
* Various bits of code, scripts & notes on how to install a modern OS onto this old tiny server

# Submodules

This repository uses Git submodules for large/externally maintained components. After cloning, initialize and fetch submodules with:

```bash
git submodule update --init --recursive
```

If you already cloned without submodules, run the same command in the repo root.

# Layout

High-level directories:

* `ofw-install-server/`: Open Firmware install server utilities (Go).
* `ofwboot/`: OpenBSD `ofwboot` bootloader (branch `tftp` == attempt to use tftp+rarp instead of nfs+bootp, switch to branch `main` for the base bootloader).
* `3d-model/`: Sun V100 10" case models.
* `misc/`: Misc configurations and scripts.

# Licenses

## Case 3D models

Sun v100 10 inch Case 3D model © 2025 by kakwa is licensed under `CC BY-SA 4.0`.

To view a copy of this license, visit [https://creativecommons.org/licenses/by-sa/4.0/](https://creativecommons.org/licenses/by-sa/4.0/).

## Scripts & Code Snippets

The various scripts and code snippets I created are under the MIT License.

`ofwboot` retains it's original OpenBSD license.
