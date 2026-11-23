# Honeywell HCE317B Space Heater with ESPHome

> [!CAUTION]
> **Fire, electric shock, and burn hazard.** The Honeywell HCE317B is a 120 V AC, 1,500 W space heater. Modifying it can compromise factory safety protections and cause serious injury, death, or property damage.
>
> **Do not bypass the tip-over switch, thermal cutoff, or any other factory protection.** Keep the heater unplugged during inspection and have any modified appliance evaluated by a qualified professional before energizing it. Keep portable heaters off when unattended or while you’re asleep.
>
> Treat the ESP32, Wi-Fi, ESPHome, and Home Assistant as controls and monitoring only. A dashboard showing “off” does not prove the heating element is de-energized. For software testing, use an LED or another low-voltage indicator with the heater disconnected.

## About this project

Smart Heater is my independent experiment with an ESP32, ESPHome, and Home Assistant using a Honeywell HCE317B space heater. I’m documenting what I learned from the first build as I revisit the project with a second unit of the same model. Honeywell and the heater’s manufacturer are unaffiliated with this project.

## What I’m documenting

- How the ESP32 reports heater status to Home Assistant and how I distinguish a command from an observed state.
- How I test the control logic on a low-voltage bench setup before connecting it to an appliance.
- What I observe when Wi-Fi drops, Home Assistant goes offline, or the ESP32 restarts.

The model number on my heater’s label is **HCE317B**. The electronics and behavior of other models or board revisions may differ. This project is experimental and the documentation is in progress.

## License and support

The code is provided as-is under the [MIT License](LICENSE). If you use or modify it, you’re responsible for evaluating your own setup and deciding whether it is safe to operate. I don’t take requests or offer installation help or troubleshooting.

If the project helped you and you’d like to leave an optional tip, you can [support my work on Ko-fi](https://ko-fi.com/ducky492).

For general guidance, see the [U.S. Consumer Product Safety Commission’s portable heater safety tips](https://www.cpsc.gov/s3fs-public/NSN-05-062026_PortableHeaterSafety_0.pdf).
