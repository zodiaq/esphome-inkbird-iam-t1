# esphome-inkbird-iam-t1
This is an experimental ESPHome implementation for Inkbird IAM-T1 based on https://devices.esphome.io/devices/Inkbird-IAM-T1.

Added:
- Return NAN value for
  - Values out of range.
  - Events unrelated to actual sensor readings.
- Setting the correct state class.

You need to modify the lines below in the file:
- HA API key
- OTA password
- Fallback AP password
- Bluetooth MAC address
