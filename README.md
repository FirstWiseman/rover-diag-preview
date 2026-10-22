# Rover Diag – web preview

A clickable preview of the Rover Diag iPhone app for a Rover 400 (HH-R) 1999 1.6 with a Webasto heater.

**All values are simulated** – this page does not connect to a car.

What it shows:

- **Overview** – 3D Rover 400 with tappable parts, paint colours and finishes, quick actions and your own value/actuator dashboard.
- **Engine** – rover-mems-agent connection (default `raspberrypi.local:8080`), ECU cable choice (`/dev/ttyUSB0` by default), live data, faults, actuator tests and adjustments for MEMS 1.9.
- **Webasto, Modules** – heater control and status, 5AS immobiliser, Bosch ABS and the RC5 airbag.
- **More → Adapter** – bridge device (Raspberry Pi, ESP32 or Arduino Nano ESP32) over Wi-Fi or Bluetooth. With the Raspberry Pi 3B: which `/dev/ttyUSBx` the Webasto (`ttyUSB3`), 5AS (`ttyUSB1`) and ABS (`ttyUSB0`) use.

Your choices (cables, paint, dashboard) are saved in the browser.

Open it at https://firstwiseman.github.io/rover-diag-preview/, then in Safari: Share → Add to Home Screen.
