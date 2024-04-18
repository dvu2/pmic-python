# pmic-python

 These MeasurementLink Python plugins makes measurements for Power Management IC's.
 
 The tests supplies power to the DUT and sinks power from the DUT and validates the specifications of the DUT by performing measurements.

## Key Features

   - Ripple
   - Output Voltage Accuracy

Click here for a detailed list of measurements and their functionality: [Measurement List](docs/measurements/meas-index.md)

## Hardware Setup
![Hardware setup](docs/images/hw-setup.png)
Instrumentation:
- NI Programmable Power Supply (PXIe-4151)
- NI Electronic Load (PXIe-4051)
- NI Scope (PXIe-5122) (used for ripple)
- Digital Pattern Instrument (PXIe-6570/1) (note: the software does not include DPI or its dependencies, but it may be required to communicate with the DUT)

Tested hardware setup:
- PXIe-4151
- PXIe-4051
- PXIe-5122 (used in ripple)
- PXIe-6570/1

## Software Dependencies
(*This section is applicable if you only want to use the pre-compiled plug-ins. If you want to open the source code, go to [software development](docs/sw-dev.md).*)  
Install from NI Package Manager:

- InstrumentStudio (2024 Q1 or higher)
- Measurement Link (2024 Q1 or higher)
- NI SDC Add-On (2023 Q4 or higher) (note: only if using DPI for DUT communication)

Download the latest NI package from the releases section of this repo or add the feed to NI Package Manager to get updates from this repo and other in this community. To use the NI Package Manager feeds, refer to this: [Subscribing to package feeds](https://github.com/NI-MeasurementLink-Plug-Ins/package-manager-feeds)

## Getting Started
When you are ready to start using the software, check out [this](docs/help.md).

## Contributing
Use the instructions in [software development](docs/sw-dev.md) for setting up a development environment and overview of the code.
