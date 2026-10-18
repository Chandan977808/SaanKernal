# SaanKernal

GKI kernel for `duchamp` (POCO X6 Pro) — Android 14, Linux 6.1 LTS, with [BakaSU](https://github.com/Baka-SU/BakaSU) root.

## Features

- GKI based on `android14-6.1-lts`
- Root: [BakaSU](https://github.com/Baka-SU/BakaSU) with SUSFS inline hooks, multi-manager support
- SUSFS v2.3.0 (kernel side vendored in [`susfs/`](susfs))
- BBRv3 TCP congestion control (default)
- NTSYNC (Proton/Wine)
- DroidSpaces support (PID, IPC, mqueue, binfmt, user namespaces)

## Build Naming

```
SaanKernal-GKI-<date>.zip
```

## Installation

See [Documentation/INSTALLATION.md](Documentation/INSTALLATION.md).

## Disclaimer

Flashing a kernel is at your own risk. Back up your data and your current `boot.img`.

## Credits

- [BakaSU](https://github.com/Baka-SU/BakaSU) — root solution
- [susfs4ksu](https://gitlab.com/simonpunk/susfs4ksu) — SUSFS
- [Wild Kernels](https://github.com/WildKernels) — BBRv3 and NTSYNC patches
- [DroidSpaces](https://github.com/ravindu644/Droidspaces-OSS)
- [PigguVerse-Action](https://github.com/handingslider/PigguVerse-Action) — original workflow this repo is based on
