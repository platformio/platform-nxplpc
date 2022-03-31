# NXP LPC: development platform for [PlatformIO](http://platformio.org)

[![Build Status](https://github.com/platformio/platform-nxplpc/workflows/Examples/badge.svg)](https://github.com/platformio/platform-nxplpc/actions)

The NXP LPC is a family of 32-bit microcontroller integrated circuits by NXP Semiconductors. The LPC chips are grouped into related series that are based around the same 32-bit ARM processor core, such as the Cortex-M4F, Cortex-M3, Cortex-M0+, or Cortex-M0. Internally, each microcontroller consists of the processor core, static RAM memory, flash memory, debugging interface, and various peripherals.

* [Home](https://registry.platformio.org/platforms/platformio/nxplpc) (home page in the PlatformIO Registry)
* [Documentation](https://docs.platformio.org/page/platforms/nxplpc.html) (advanced usage, packages, boards, frameworks, etc.)

# Usage

1. [Install PlatformIO](http://platformio.org)
2. Create PlatformIO project and configure a platform option in [platformio.ini](https://docs.platformio.org/page/projectconf.html) file:

## Stable version

```ini
[env:stable]
platform = nxplpc
board = ...
...
```

## Development version

```ini
[env:development]
platform = https://github.com/platformio/platform-nxplpc.git
board = ...
...
```

# Configuration

Please navigate to [documentation](https://docs.platformio.org/page/platforms/nxplpc.html).
