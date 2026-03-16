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
| ESP32 Development Board | 1 | Main microcontroller used to run the project | https://www.aliexpress.com/item/4000079648503.html | $3.61 | $3.61 |
| ST7735 TFT LCD Display | 1 | Small SPI display used to show track information | https://www.aliexpress.com/item/32996979276.html | $2.49 | $2.49 |
| Rotary Encoder (with knob) | 1 | Used for volume or menu control | https://www.aliexpress.com/item/32587006925.html | $0.60 | $0.60 |
| Momentary Push Buttons | 3 | Used for playback controls | https://www.aliexpress.com/item/32982255849.html | $1.53 | $1.53 |
| Keycaps | 3 | Caps for the push buttons | https://www.aliexpress.com/item/1005001628106767.html | $3.27 | $3.27 |
| Jumper Wires | 1 pack | Used to connect the components | https://www.aliexpress.com/item/4000005166772.html | $1.00 | $1.00 |
| USB Cable | 1 | Used to power and program the ESP32 | https://www.aliexpress.com/item/32834219764.html | $4.27 | $4.27 |

**Estimated Electronics Cost: ~$16.77**

**Estimated Total Cost (including printed parts): ~$18.77**
