# Ada library for Raspberry Pi3 (rpb_ada)

[![Build Status](https://travis-ci.org/ogorodnik/rpb_ada.svg?branch=master)](https://travis-ci.org/ogorodnik/rpb_ada)

This is an Ada library for Raspberry Pi3 ( bcm2837B0 ).
It provides support for GPIO, SPI, I2C, etc.

The main purpose of creating it - using it in education for teaching
programming and robotics, so the main concept is: easy to use and
preventing incorrect usage as possible.

Also it has support for following extension shields:
 - WAVESHARE High-Precision AD/DA Expansion Board (SKU: 11010)
 - WAVESHARE Servo Driver HAT (SKU: 15275)

# Install

For using it you should install:
 - GNU Ada compiller (gnat-4.9)
 - multi-language-extensible build tool (grpbuild-2014dfsg-1)
 - integrated development environment for C and Ada (gnat-gps-5.3-dfsg-1)
in your Raspbian package manager.

For starting: launch gnat-gps and select some project from the examples direstory.
