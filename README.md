# IoT Air Conditioning Project Spec

## Goals
  - The AC unit must be controlled over the local wireless network
  - The AC unit must be able to be turned on and off remotely without impeding the
    standard function inteded by the manufacturer
  - The AC unit must must serve an interface accessible via the local wireless
    network
  - Trigger the unit via the web gui

## Hardware
  - Window unit air conditioner
  - Raspberry pi B
  - Hardware laying around the house

## Future Work
Future versions of this project will expand upon the baseline functionality
outlined in this document in no particular order:

  - Ephermeral metrics collection of the following:
    - Ambient temperature (f/c)
    - AC unit temperature out (f/c)
    - Ambient humidity (%)
  - Air Filtration 
    - Filtration fan speed (rpm)
    - Dust particle measuring
    - Filter Life warning light
  - Telemetry service
  - Auto Shut-Off
  - Metrics collection
  - Stateful metrics retention via a vps hosted on vultr
  - Control of unit over internet



