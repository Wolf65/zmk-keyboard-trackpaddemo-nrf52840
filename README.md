# ZMK Trackpad Demo

A minimal ZMK keyboard demonstrating trackpad integration using the Azoteq TPS43 sensor on a nRF52840. This demo uses the [geeksville/zmk_driver_azoteq](https://github.com/geeksville/zmk_driver_azoteq) driver.

## Hardware

| Component        | Details                                     |
| ---------------- | ------------------------------------------- |
| MCU board        | nice!nano (nRF52840)                        |
| Trackpad sensor  | Azoteq TPS43                                |

### Pin mapping

| Signal         | Pin    |
| -------------- | ------ |
| I2C SDA        | P0.17  |
| I2C SCL        | P0.20  |
| RDY            | P1.07  |
| RST            | P1.02  |

## ZMK version

This config targets the ZMK `main` branch (slated for release as **v0.4**), as of 2026-06-28. Things may break as `main` evolves before the v0.4 release.

## License

MIT — see [LICENSE](LICENSE).

---

> Parts of this project were developed with assistance from AI tools.
