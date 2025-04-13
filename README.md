# srjv
SR-JV80 Programmable Expansion Card with ESP32 Wi-Fi
- Product info page at https://www.ddzheng.cc/?page_id=666
- Blog post at https://www.ddzheng.cc/?p=617

# Hardware Info
- ESP32-S3 Wroom module requires at least 2 MB Flash (No OTA) or 4 MB (with OTA).
- The NOR flash can be TSSOP 48 or 56 pin, 8 MB or more, 70ns or faster, with byte (8-bit) mode support. Regularly used for production is MX29LV640
- Connector is 40 pin SCSI all plastic connector or similar. The original card use MOLEX 52326-0401
- Reverse taped LED is only required for SMT production. For hand assembling regular 1206 LED can be used.

# Fabricating
4-layer board. Can also be made with 2 layers without modification. Assemble as indicated (DNP = do not populate) in schematic.

# Licsensing

Copyright Connor Zheng 2025.


This source describes Open Hardware and is licensed under the CERN-OHLW v2 or later. You may redistribute and modify this documentation and make products using it under the terms of the CERN-OHL-W v2 [https:/cern.ch/cern-ohl](https:/cern.ch/cern-ohl). This documentation is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A PARTICULAR PURPOSE. Please see the CERN-OHL-W v2 for applicable conditions.


Source location: [https://github.com/connorzheng97/srjv](https://github.com/connorzheng97/srjv)


As per CERN-OHL-W v2 section 4.1, should You produce hardware based on these sources, You must maintain the Source Location visible on the external case and PCB top layer silkscreen of the SRJV or other product you make using this documentation.
