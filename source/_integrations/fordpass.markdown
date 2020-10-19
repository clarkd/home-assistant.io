---
title: FordPass
description: Instructions on how to integrate FordPass (Ford Vehicle) into Home Assistant.
ha_category:
  - Car  
  - Lock
  - Binary Sensor
ha_release: 0.117
ha_iot_class: Cloud Polling
ha_config_flow: true
ha_codeowners:
  - '@clarkd'
ha_domain: fordpass
---

The `FordPass` integration offers integration with the [FordPass](https://www.ford.co.uk/owner/owner-services/fordpass) API/app and provides various entities, e.g. lock to unlock/lock the vehicle and binary sensors for doors, windows, ignition and more.

This integration provides the following platforms:

- Lock - Lock/Unlock the doors
- Binary Sensor - Tracks state of Doors (open/closed), Windows (open/closed), Ignition (on/off), Alarm (on/off)

## Configuration

Home Assistant offers the FordPass integration through **Configuration** -> **Integrations** -> **Fordpass**.

Enter username, password for FordPass and the VIN number of your vehicle and then continue.