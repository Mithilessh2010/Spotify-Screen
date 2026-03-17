# Spotify Display

This project is a small desktop display that shows and controls music playback. It uses an ESP32 and a small TFT screen to show the current track. A rotary encoder and a few buttons let you control playback.

I chose this project because it looked interesting and helped me learn more about using SPI displays with a microcontroller. It also makes it easy to control music without opening an app on your phone or computer.

<img width="810" height="598" alt="image" src="https://github.com/user-attachments/assets/efe84ceb-49e6-471f-a237-c6d7e8fcde46" />

---

# CAD

The case for this project has two simple parts: a front case and a back cover.

The front case holds the screen, buttons, and rotary encoder. It also has a slot that keeps the ESP32 board in place. The back cover snaps onto the front and has an opening for the power cable.

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

Both printed parts are included together in a single `.step` file in the repository.

---

## Electronics

| Part | Quantity | Description | Link | Cost | Total |
|-----|-----|-----|-----|-----|-----|
| ESP32 Development Board | 1 | Main microcontroller used to run the project | https://a.co/d/02p5Ifkj | $10 | $10 |
| ST7735 TFT LCD Display | 1 | Small SPI display used to show track information | https://a.co/d/06It8hal | $9.95 | $9.95 |
| Rotary Encoder (with knob) | 1 | Used for volume or menu control | https://a.co/d/0dQ7lI8W | $8.89 | $8.89 |
| Mechanical Switches | 3 | Used for playback controls | https://a.co/d/06fXIy8R | $9.99 | $9.99 |
| Keycaps | 3 | Caps for the push buttons | https://a.co/d/0duP7i0d | $3.18 | $3.18 |
| Jumper Wires | 1 pack | Used to connect the components | https://a.co/d/01FAON4C | $7.00 | $7.00 |

**Estimated Electronics Cost: ~$45.80**

**Estimated Total Cost (including printed parts): ~$47.87**
