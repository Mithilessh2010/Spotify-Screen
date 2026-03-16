# Spotify Display

This project is a small desktop display that shows and controls music playback. It uses an ESP32 and a small TFT screen to display information like the current track. A rotary encoder and a few buttons are used to control playback.

I chose this project because it looked interesting and gave me a chance to learn more about using SPI displays with a microcontroller. It is also a useful way to control music without needing to open an app on a phone or computer.

<img width="810" height="598" alt="image" src="https://github.com/user-attachments/assets/efe84ceb-49e6-471f-a237-c6d7e8fcde46" />

---

# CAD

The enclosure for this project is made from two simple parts: a front case and a back cover.

The front case holds the screen, buttons, and rotary encoder. It also has a small slot to keep the ESP32 board in place. The back cover snaps onto the front using a small lip and has an opening for the power cable.

The parts are designed to be easy to print and assemble.

<img width="909" height="662" alt="image" src="https://github.com/user-attachments/assets/d3e5170e-04d7-4ed3-b15a-ee222a0febc4" />

---

# Firmware

The firmware runs on the ESP32 and handles the display updates and button inputs. It communicates with Spotify and updates the screen with the current track information.

The rotary encoder and buttons send commands such as play/pause, next track, and volume control.

---

# Bill of Materials (BOM)

## Printed Parts

| Part | Quantity | Estimated Cost |
|-----|-----|-----|
| Front Case | 1 | $1 |
| Back Cover | 1 | $1 |

Both printed parts are included together in a single `.step` file in the repository to make printing easier.

---

## Electronics

| Part | Quantity | Description | Cost (USD) | Total |
|-----|-----|-----|-----|-----|
| ESP32 Development Board | 1 | Main microcontroller used to run the project | $8.00 | $8.00 |
| ST7735 TFT LCD Display | 1 | Small SPI display used to show track information | $9.95 | $9.95 |
| Rotary Encoder (with knob) | 1 | Used for volume or menu control | $2.00 | $2.00 |
| Momentary Push Buttons | 3 | Used for playback controls | $0.25 | $0.75 |
| Keycaps | 3 | Caps for the push buttons | $0.50 | $1.50 |
| Jumper Wires | 1 pack | Used to connect the components | $3.00 | $3.00 |
| USB Cable | 1 | Used to power and program the ESP32 | $3.00 | $3.00 |

**Estimated Total Cost: ~$30.70**
