#### Example `CONFIGURATION.md`

```markdown
# Configuration Guide

## Overview

This document provides instructions for configuring the EcoWay system.

## Configuration File Example

You can use the following example to create your `config.yml` file:

```yaml
# config/config.yml

# Bluetooth Settings
bluetooth:
  beacons:
    - uuid: "12345678-1234-1234-1234-123456789abc"
      name: "Beacon1"
      location: "Entrance Hall"
    - uuid: "abcdef12-3456-7890-abcd-ef1234567890"
      name: "Beacon2"
      location: "Conference Room"
  scan_interval: 5

# Navigation Settings
navigation:
  start_point:
    name: "Main Entrance"
    coordinates: 
      latitude: 40.712776
      longitude: -74.005974
  end_point:
    name: "Office 101"
    coordinates: 
      latitude: 40.712776
      longitude: -74.015974

# User Settings
user:
  language: "en"
  volume: 75

# Logging Settings
logging:
  enabled: true
  file_path: "logs/application.log"
