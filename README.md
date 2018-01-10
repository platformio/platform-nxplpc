# NXP LPC: development platform for [PlatformIO](http://platformio.org)
[![Build Status](https://travis-ci.org/platformio/platform-nxplpc.svg?branch=develop)](https://travis-ci.org/platformio/platform-nxplpc)
[![Build status](https://ci.appveyor.com/api/projects/status/gm98eo04per1je25/branch/develop?svg=true)](https://ci.appveyor.com/project/ivankravets/platform-nxplpc/branch/develop)

The NXP LPC is a family of 32-bit microcontroller integrated circuits by NXP Semiconductors. The LPC chips are grouped into related series that are based around the same 32-bit ARM processor core, such as the Cortex-M4F, Cortex-M3, Cortex-M0+, or Cortex-M0. Internally, each microcontroller consists of the processor core, static RAM memory, flash memory, debugging interface, and various peripherals.

* [Home](http://platformio.org/platforms/nxplpc) (home page in PlatformIO Platform Registry)
* [Documentation](http://docs.platformio.org/page/platforms/nxplpc.html) (advanced usage, packages, boards, frameworks, etc.)

# Usage

1. [Install PlatformIO](http://platformio.org)
2. Create PlatformIO project and configure a platform option in [platformio.ini](http://docs.platformio.org/page/projectconf.html) file:

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

Please navigate to [documentation](http://docs.platformio.org/page/platforms/nxplpc.html).
