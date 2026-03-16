# Spotify Display

This project is a small desktop display that shows and controls music playback. It uses an ESP32 and a small TFT screen to show the current track. A rotary encoder and a few buttons let you control playback.

I chose this project because it looked interesting and helped me learn more about SPI displays with a microcontroller. It also makes it easy to control music without opening an app on your phone or computer.

<img width="810" height="598" alt="image" src="https://github.com/user-attachments/assets/efe84ceb-49e6-471f-a237-c6d7e8fcde46" />

---

## CAD

The case for this project has two simple parts: a front case and a back cover.

The front case holds the screen, buttons and rotary encoder. It also has a small slot for the ESP32 board. The back cover snaps onto the front using a lip and has an opening for the power cable.

The parts are easy to print and assemble.

<img width="909" height="662" alt="image" src="https://github.com/user-attachments/assets/d3e5170e-04d7-4ed3-b15a-ee222a0febc4" />

---

## Firmware

The firmware runs on the ESP32 and handles the display updates and button inputs. It talks to Spotify and updates the screen with the current track. The rotary encoder and buttons send commands such as play/pause, next track and volume control.

---

## Bill of Materials (BOM)

### Printed Parts

| Part       | Quantity | Estimated Cost |
|------------|----------|----------------|
| Front Case | 1        | $1             |
| Back Cover | 1        | $1             |

Both printed parts are included together in a single `.step` file in the repository to make printing easier.

### Electronics

This table lists the electronic parts used in the build. Each part has a link to an example listing on AliExpress and an approximate cost. Use these links to check the current price, since costs can change. Some parts are sold only in packs, so the price shown is for the whole pack.

| Part/Component                    | Qty/Pack                      | Description                                            | AliExpress Listing (example)                                                                  | Cost (USD) | Total (USD) |
|----------------------------------|-------------------------------|--------------------------------------------------------|------------------------------------------------------------------------------------------------|-----------:|------------:|
| **ESP32 Development Board**      | 1                             | Main microcontroller used to run the project           | [ESP32‑DevKitC core board](https://www.aliexpress.com/item/4000079648503.html) (Alitools price ≈1.42–3.61 USD:contentReference[oaicite:0]{index=0}) | $3.00      | $3.00       |
| **ST7735 TFT LCD Display**       | 1                             | Small SPI display used to show track information       | [ST7735/7789 TFT module](https://www.aliexpress.com/item/32996979276.html) (Alitools price ≈1.57–2.49 USD:contentReference[oaicite:1]{index=1})   | $2.00      | $2.00       |
| **Rotary Encoder (with knob)**   | 1 set                         | EC11 rotary encoder with knob for volume/menu control  | [1‑Set 360° rotary encoder + knob](https://www.aliexpress.com/item/32587006925.html) – price around $0.60:contentReference[oaicite:2]{index=2} | $0.60      | $0.60       |
| **Momentary Push Buttons**       | 1 pack (10 pcs)               | Tactile push buttons used for playback controls        | [10 pcs PBS110 momentary push buttons](https://www.aliexpress.com/item/32982255849.html) – pack price ≈ $1.53:contentReference[oaicite:3]{index=3} | $1.53      | $1.53       |
| **Keycaps for push buttons**     | 1 pack (50 pcs)               | Plastic caps for 12×12 mm tactile switches             | [50 pcs long‑foot keycaps](https://www.aliexpress.com/item/1005001628106767.html) – pack price ≈ $3.21–3.27 USD:contentReference[oaicite:4]{index=4} | $3.27      | $3.27       |
| **Jumper Wires (solderless)**    | 1 pack (65 pcs)               | Flexible jumper wires for connecting components        | [65 pcs breadboard jumper wires](https://www.aliexpress.com/item/4000005166772.html) – pack price around $1 :contentReference[oaicite:5]{index=5} | $1.00      | $1.00       |
| **USB Cable**                    | 1                             | USB‑A to Micro‑USB cable for powering/programming ESP32 | [Micro‑USB data/charging cable](https://www.aliexpress.com/item/32834219764.html) – price range ≈0.99–4.27 USD:contentReference[oaicite:6]{index=6} | $0.99      | $0.99       |

**Estimated Electronics Cost:** ~**$12.39** (using representative prices). Including the printed parts (~$2) gives an estimated total build cost around **$14.39**. Shipping and taxes are not included and may vary by region.

---
