# RTClib [![Build Status](https://github.com/qnimble/RTClib/workflows/Arduino%20Library%20CI/badge.svg)](https://github.com/qnimble/RTClib/actions)

This is a fork for Adafruit's fork of JeeLab's fantastic real time clock library for Arduino. This fork removes support for RTC hardware and is a minimal date/time library

Please note that dayOfTheWeek() ranges from 0 to 6 inclusive with 0 being 'Sunday'.

## Code formatting and clang-format
The code should be formatted according to the [LLVM Coding Standards](https://llvm.org/docs/CodingStandards.html), which is the default of the clang-format tool.  The easiest way to ensure conformance is to [install clang-format](https://llvm.org/builds/) and run

```shell
clang-format -i <source_file>
```

See [Formatting with clang-format](https://learn.adafruit.com/the-well-automated-arduino-library/formatting-with-clang-format) for details.

Written by JeeLabs
MIT license, check license.txt for more information
All text above must be included in any redistribution
