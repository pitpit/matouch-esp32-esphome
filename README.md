# MaTouch ESPHome Support

This project provides [ESPHome](https://esphome.io) support for various MaTouch devices as configuration packages.

## Supported Devices

| Device | Backlight | Display | Touchscreen | Rotary Enc. | Idle Screen | Deep Sleep |
|--------|-----------|---------|-------------|-------------|-------|------------|
| [MaTouch ESP32-S3 Rotary IPS Display with Touch 2.1" ST7701](https://www.makerfabs.com/matouch-esp32-s3-rotary-ips-display-with-touch-2-1-st7701.html) | ✅ Supported | ✅ Supported |  ✅ Supported | ✅ Supported | ✅ Supported |✅ Supported |
| [MaTouch ESP32-S3 Rotary IPS Display 1.28" GC9A01](https://www.makerfabs.com/matouch-esp32-s3-rotaryips-display1-28-gc9a01.html) | 🚧 In Progress |

## Usage

You can use these configurations as [ESPHome Packages](https://esphome.io/components/packages.html) in your device configuration:

```yaml
packages:
  - github://pitpit/matouch-esp32-esphome/packages/matouch-esp32-s3-rotary-ips-display-st7701.yaml@main

```

## Demo

To try out the included demo configuration:

1. Clone this repository:
   ```bash
   git clone https://github.com/pitpit/matouch-esp32-esphome.git
   cd matouch-esp32-esphome
   ```

2. Run the demo configuration:
   ```bash
   esphome run demo-st7701.yaml
   ```

This will compile and upload a full demo featuring display, touch, and rotary encoder functionality.

Then compile and upload as usual.
