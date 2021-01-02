.. _firmware:

Firmware
========

This page desribes firmware that this documentation has been tested with.
Firmware can be upgraded over the network.

Firmware family "D"
-------------------

Firmware consists of two files. I have seen following versions:

- 1.99.18 - probably first public version
- 1.99.20
- 1.99.24
- 1.99.30
- 2.0.0
- 2.0.8
- 2.0.12
- 2.0.13
- 2.0.19
- 2.0.22-mqtt - adds MQTT support
- 2.1.0
- 2.1.1-net
- 2.1.2-net
- 2.3.5 - last version upgraded by application
- 2.3.8

Firmware family "F"
-------------------

Firmware file is `encrypted using host generated key`_. I have seen following versions:

- 2.2.1 - shipped with a device, maybe first public version?
- 2.2.2
- 2.4.2 - adds MQTT and brightness support
- 2.4.6 - seems to incorrectly report `frame_rate: 1` in `gestalt` API call
- 2.4.14
- 2.4.16
- 2.4.22
- 2.4.25
- 2.4.30 - introduced SSID encryption for client setup
- 2.5.6 - adds UUIDs to effects

Firmware family "G"
-------------------

Firmware file is `encrypted using host generated key`_. I have seen following versions:

- 2.4.21 - shipped with a device
- 2.4.25 - seems to incorrectly report `frame_rate: 1` in `gestalt` API call
- 2.4.30 - introduced SSID encryption for client setup
- 2.5.6 - adds UUIDs to effects and playlists


.. _`encrypted using host generated key`: https://docs.espressif.com/projects/esp-idf/en/latest/esp32/security/flash-encryption.html#using-host-generated-key
