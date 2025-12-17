# Waveshare IMX219-77 Camera Module

## Product
**Sensor:** Sony IMX219 (8 MP)  
**Link:** https://www.waveshare.com/wiki/IMX219-77_Camera

## Key Specifications

| Parameter        | Value |
|------------------|-------|
| Resolution       | 3280 × 2464 (8 MP) |
| Sensor Size      | 1/4″ CMOS |
| Lens FOV         | ~77° |
| Focal Length     | 2.96 mm |
| Aperture         | ~F2.8 |
| Interface        | MIPI-CSI |
| Power            | 3.3 V (host-supplied) |
| Module Size      | ~25 × 24 mm |

## Compatibility
- Raspberry Pi (CSI)
- NVIDIA Jetson Nano
- Other MIPI-CSI SBCs (driver dependent)

## Usage Notes
- Connect via CSI camera interface.
- Tested using `libcamera` on Raspberry Pi.
- Supports full-resolution still capture.

## Test Command (Raspberry Pi)
```bash
libcamera-still -o image.jpg --width 3280 --height 2464
