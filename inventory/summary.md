# Hardware inventory — 2026-11-22

## Status at a glance

- **Inventory records:** 210 item/lot/component records (parent assemblies and installed components linked)
- **Records associated with photographs:** 201
- **Photo-verified / owner-confirmed hardware:** 175 (some enclosed items owner-confirmed; no working-status implied)
- **Photo-supported / tentative identifications or packaging only:** 28
- **Previously reported, not yet photographed:** 7
- **Photo intake records:** 181

These are **record and photo counts**, not counts of verified working devices. A photographed retail box does not establish that electronic contents are present unless separately confirmed.

- **Records lacking direct item photographs:** 9 (some contents independently confirmed by owner)

## Latest batch — 028 (3 photographs, 3 new records; more small sensor breakouts)

| ID | Item | Quantity | Photo |
| --- | --- | ---: | --- |
| HW-0208 | BME/BMP280 barometric sensor breakout, 4-pin I2C style (variant undetermined) | 1 | `1000063328.jpg` |
| HW-0209 | VL53L0X laser time-of-flight distance sensor module (GY-VL53L0X) | 1 | `1000063329.jpg` |
| HW-0210 | GY-271 three-axis magnetometer (compass) module, HMC5883L type | 1 | `1000063330.jpg` |

**Confidence notes:** The VL53L0X module's silkscreen and twin-aperture sensor are legible (high). The 4-pin BME/BMP280 board is a second, physically different module from the 6-pin GY-B11 board HW-0205 — not a re-photo of it — and its sensor marking is too faint to separate BME280 from BMP280 (medium). The GY-271 shows only its back; its printed designation is the HMC5883L compass module, but some GY-271 boards carry a QMC5883L, which a front photo would settle (medium). No working condition claimed. All three photo binaries are stored in the repo (`photos/2026/11/`, EXIF stripped).

[Batch 028 detail](batches/2026-11-22-028.md).

## Earlier batch — 027 (8 new photographs, 7 new records; small I2C and sensor breakouts)

Eight new photos and seven new items; a ninth upload was a byte-identical resend of the batch 026 TCS3200 photo and was not logged twice. The Aether potentiometer module was photographed from both sides (one record). Two purple GY modules show only their backs.

| ID | Item | Quantity | Photo |
| --- | --- | ---: | --- |
| HW-0201 | Aether X9C103S digital potentiometer module | 1 | `1000063320.jpg`, `1000063321.jpg` |
| HW-0202 | Electret microphone amplifier module, adjustable gain (MAX4466 type) | 1 | `1000063322.jpg` |
| HW-0203 | Non-contact IR temperature sensor module, MLX90614 type (GY-906 type) | 1 | `1000063323.jpg` |
| HW-0204 | GY-91 ten-axis sensor module, MPU-9250 + BMP280 (HW-612 PCB) | 1 | `1000063324.jpg` |
| HW-0205 | GY-BME/P280 barometric sensor breakout (BME280 or BMP280) | 1 | `1000063325.jpg` |
| HW-0206 | CJMCU TCA9548A 8-channel I2C multiplexer module | 1 | `1000063326.jpg` |
| HW-0207 | GY-219 INA219 current and power monitor module | 1 | `1000063327.jpg` |

**Confidence notes:** The X9C103S chip marking and the TCA9548A silkscreen plus its PW548A chip marking are legible (high). The HW-612 back's PCB code and pin set match the documented GY-91 (MPU-9250 IMU + BMP280), but its sensors were not photographed (medium). The GY-219's model is its own printed designation, but only the back was photographed (medium). The GY-BME/P280's fitted chip — BME280 or BMP280 — is not clearly visible, so the variant stays undetermined (medium). The microphone module's amplifier chip sits on its unphotographed reverse (MAX4466 type, medium), and the IR module's can carries no legible model text (MLX90614 type, medium). Front photos of HW-0204 and HW-0207 and a sensor close-up of HW-0205 would settle the open points. No working condition claimed. All eight photo binaries are stored in the repo (`photos/2026/11/`, EXIF stripped).

[Batch 027 detail](batches/2026-11-22-027.md).

## Earlier batch — 026 (9 photographs, 7 new records; sensor and shield modules)

Nine photos, seven new items. Two items were photographed from both sides and are single records, as the owner confirmed: the PIR module (dome front + held reverse) and the DS18B20 bag (devices front + labelled back). None duplicates an existing record.

| ID | Item | Quantity | Photo |
| --- | --- | ---: | --- |
| HW-0194 | HC-SR04 ultrasonic distance sensor module | 1 | `1000063311.jpg` |
| HW-0195 | Tiny RTC DS1307 real-time clock module (I2C), 24C32 EEPROM on board | 1 | `1000063312.jpg` |
| HW-0196 | PIR motion sensor module, HC-SR501 type (D-SUN PCB, BISS0001) | 1 | `1000063313.jpg`, `1000063314.jpg` |
| HW-0197 | Arduino Sensor Shield v5.0 | 1 | `1000063315.jpg` |
| HW-0198 | Colorduino-type 8×8 RGB LED matrix driver board (ATmega328P / DM163 / M54564) | 1 | `1000063316.jpg` |
| HW-0199 | Dallas DS18B20 digital temperature sensors, TO-92 | 5 | `1000063317.jpg`, `1000063318.jpg` |
| HW-0200 | TCS3200 color sensor module (GY-31 type) | 1 | `1000063319.jpg` |

**Confidence notes:** HC-SR04, Tiny RTC and Sensor Shield carry legible on-board model text (high). The DS18B20 count of 5 comes from the bag front; three devices show legible `DALLAS 18B20` markings and the bag is hand-labelled "DS18B20 temp. sensor". The PIR's BISS0001 layout is the standard HC-SR501 design but the board prints no model name (medium for the designation, certain for the type). The matrix driver board's three chips (MEGA328P, DM163, M54564AFP) and RED/GREEN/BLUE headers identify the Colorduino family, but it has no product silkscreen and no matrix panel attached (medium). The TCS3200 module's chip carries no legible text; identification rests on its four-LED layout and S0–S3/OUT pinout (medium). The Tiny RTC's reverse was not photographed, so no backup battery is claimed. No working condition claimed. All nine photo binaries are stored in the repo (`photos/2026/11/`, EXIF stripped).

[Batch 026 detail](batches/2026-11-22-026.md).

## Earlier batch — 025 (2 follow-up photographs, 0 new records; last three unidentified DIP ICs resolved)

Two close-ups (`1000063309.jpg`, `1000063310.jpg`) resolve the three black DIP ICs left unidentified in batch 024 photo `1000063301.jpg`. The records keep their existing IDs; nothing was added or double-counted.

| ID | Resolved item | Quantity | Photo |
| --- | --- | ---: | --- |
| HW-0189 | STMicroelectronics `M74HC04B1` hex inverter IC, DIP-14 | 1 | `1000063301.jpg`, `1000063309.jpg` |
| HW-0190 | STMicroelectronics `L293D` motor driver IC, DIP-16 | 1 | `1000063301.jpg`, `1000063310.jpg` |
| HW-0191 | Texas Instruments `NE555P` timer IC, DIP-8 | 1 | `1000063301.jpg`, `1000063310.jpg` |

**Identification basis:** ST logo + `M74HC04B1` legible after rotating `1000063309.jpg` 180°; ST logo + `L293D` and TI logo + `NE555P` legible in `1000063310.jpg`; pin counts match each part (14 / 16 / 8). All seven loose DIPs in `1000063301.jpg` are now identified. Still unresolved from batch 024: the exact chip count inside the two `MAX7219CNG` tubes (HW-0192, quantity null). No working condition claimed. Unlike batches 001–024, these two photo binaries are stored in the repo (`photos/2026/11/`, EXIF stripped).

[Batch 025 detail](batches/2026-11-22-025.md).

## Earlier batch — 024 (7 photographs including one follow-up, 11 new records; exact DIP markings prioritized)

| IDs | Item or lot | Quantity | Photo |
| --- | --- | ---: | --- |
| HW-0183 | Slotted optical interrupter / speed detector modules, 3-pin | 10 | `1000063299.jpg` |
| HW-0184 | Dual-channel TX/RX logic-level interface boards (UART-style) | 2 | `1000063300.jpg` |
| HW-0185 | Handheld 17-key infrared remote control (numeric and navigation) | 1 | `1000063304.jpg` |
| HW-0186 | Three-pin infrared remote receiver breakout module with jumper leads | 1 | `1000063304.jpg` |
| HW-0187 | 4N35 phototransistor optocouplers, DIP-6 white package | 2 | `1000063301.jpg` |
| HW-0188 | NXP `74HC595N` 8-bit shift-register ICs, DIP-16 | 2 | `1000063301.jpg`, `1000063308.jpg` |
| HW-0189 | STMicroelectronics `M74HC04B1` hex inverter IC, DIP-14 (resolved in batch 025) | 1 | `1000063301.jpg`, `1000063309.jpg` |
| HW-0190 | STMicroelectronics `L293D` motor driver IC, DIP-16 (resolved in batch 025) | 1 | `1000063301.jpg`, `1000063310.jpg` |
| HW-0191 | Texas Instruments `NE555P` timer IC, DIP-8 (resolved in batch 025) | 1 | `1000063301.jpg`, `1000063310.jpg` |
| HW-0192 | MAX7219CNG LED-matrix driver integrated circuits in two storage tubes | Unknown (2 tubes) | `1000063303.jpg` |
| HW-0193 | Texas Instruments SN74HC595N 8-bit shift register ICs, DIP-16 | 10 | `1000063302.jpg` |

**Definite part markings:** Two NXP `74HC595N` DIP-16 shift registers (HW-0188); ten TI `SN74HC595N` DIP-16 shift registers (HW-0193); two `4N35` optocouplers (HW-0187); and `MAX7219CNG` DIP-24 display-driver chips in two plastic tubes (HW-0192). The exact MAX7219 chip count remains **unknown** because the two tubes conceal/overlap individual chips, so the quantity is null, not two.

**Three black DIP chips unreadable in this batch** — one lower horizontal (HW-0189), one lower long/vertical (HW-0190), and one small DIP-8 (HW-0191) — **were resolved in batch 025** as `M74HC04B1`, `L293D` and `NE555P` respectively. The two upper-foam ICs are now verified as NXP `74HC595N` from close-up `1000063308.jpg` (HW-0188). No speculative chip IDs were entered.

**Other photographic hardware:** ten 3-pin optical slotted modules (HW-0183), two UART-style TX/RX level interface boards (HW-0184), one IR remote (HW-0185), one IR receiver board with adjacent jumper lead accessories (HW-0186).

**Deduplication and caveats:** Loose `MAX7219CNG` chips are not the previously inventoried assembled HW-0132 MAX7219 LED matrix board; loose jumper leads accompanying the IR receiver are accessories rather than another generic jumper-wire lot. No working condition claimed. Photos remain conversation attachments; no binary photo copies uploaded.

[Batch 024 detailed audit](batches/2026-11-22-024.md).

## Earlier batch — 023 (1 photograph, 13 item-type/organizer records; partial visibility)

Photo: `1000063298.jpg`. One clear divided hardware organizer with numerous discrete components, plus partly cropped compartments on top and right.

| ID | Item | Visible quantity |
| --- | --- | ---: |
| HW-0170 | Clear compartment organizer for mixed loose electronics | 1 |
| HW-0171 | Assorted axial through-hole resistors (blue and beige body) | 7 |
| HW-0172 | Orange ceramic disc capacitors, assorted sizes | 8 |
| HW-0173 | Black axial leaded diodes, assorted | 4 |
| HW-0174 | Radial electrolytic capacitors, mixed sizes | 6 |
| HW-0175 | Loose three-lead TO-92-like semiconductor devices | 4 |
| HW-0176 | Large TO-220 three-lead power semiconductor | 1 |
| HW-0177 | Black multi-contact rectangular connector housing | 1 |
| HW-0178 | Small angled multi-pin header or connector | 1 |
| HW-0179 | Black flanged hollow plastic button-cap-like piece | 1 |
| HW-0180 | Red plastic button-cap-like piece (partly obscured) | 1 |
| HW-0181 | Loose glass cartridge fuses in organizer | 2 |
| HW-0182 | Unidentified small metal mechanical part | 1 |

**Counts & scope:** There are 7 resistors (5 blue, 2 beige); 8 orange ceramic disc capacitors; 4 diode-like axial devices; 6 electrolytic-looking radial capacitors (5 bottom center + 1 small upper-left); 4 clearly visible small three-lead TO-92-like semiconductors (a possible additional obscured part was not counted); 1 large TO-220 device; 2 separately visible cartridge fuses. The 2 red/black plastic cap-like parts, 2 connectors and 1 metal mechanism have uncertain precise identity. The 1 container record is for the physical tray **only**, not another count of its electronics.

**Deduplication:** The two fuses are not the earlier one in the T3.15A-labelled packet (HW-0162); do not copy the earlier bag's rating. The organizer does not reuse the jumper-wire organizer HW-0103. No separate counts for metal leads or hidden objects. Further photos may refine type, values and quantity.

**Evidence limitation:** Original photo is referenced in the intake log, but the JPG binary is not stored in GitHub. [Batch 023 detail](batches/2026-11-22-023.md).

## Earlier batch — 022 (9 photographs; 11 new item/variant records, 1 existing item enriched)

| ID | Item | Quantity | Photo |
| --- | --- | ---: | --- |
| HW-0159 | Small white-plunger tactile switches | 3 | `1000063284.jpg` |
| HW-0160 | Larger black-center square tactile switches | 6 | `1000063284.jpg` |
| HW-0161 | 4×4 sixteen-key membrane keypad | 1 | `1000063290.jpg` |
| HW-0162 | Spare glass fuse, T3.15A label | 1 | `1000063291.jpg` |
| HW-0163 | Keyes KY-040-type rotary encoder module | 1 | `1000063292.jpg` |
| HW-0164 | B100K (100 kΩ nominal) rotary potentiometers | 2 | `1000063293.jpg` |
| HW-0165 | B10K (10 kΩ nominal) rotary potentiometers | 2 | `1000063293.jpg` |
| HW-0166 | B50K (50 kΩ nominal) rotary potentiometer | 1 | `1000063293.jpg` |
| HW-0167 | CanaKit PiSwitch inline pushbutton power switch | 1 | `1000063294.jpg` |
| HW-0168 | Olympus VF-RM7 wired REC/PAUSE remote | 1 | `1000063295.jpg` |
| HW-0169 | Apple Remote A1156 IR controller | 1 | `1000063296.jpg`, `1000063297.jpg` |

**Deduplication:** The two Apple Remote photographs are opposite sides of one device; the LCD Keypad Shield cropped in `1000063284.jpg` is an existing HW-0151 unit, not another shield. The nine new tactile switches are loose hardware, not integrated buttons on any shield. The five potentiometers are kept in three separate resistance groups. No assumptions of tested working status.

**Unverified:** Exact caps for the larger switches, fuse body/rating independent of packaging, potentiometer resistance measured values, PiSwitch USB connector details, remote compatibility and operation. The image binaries are referenced but not uploaded to GitHub. [Batch 022 details](batches/2026-11-22-022.md).

## Earlier batch — 021 (9 photographs; 11 new records, 2 LED-bar records enriched)

| ID | Item | Quantity | Photo |
| --- | --- | ---: | --- |
| HW-0148 | Male-to-male Dupont jumper-wire bundle | 1 bundle | `1000063277.jpg`, `1000063278.jpg` |
| HW-0149 | Mixed-end Dupont jumper-wire bundle (connector genders partly unverified) | 1 bundle | `1000063278.jpg` |
| HW-0150 | Color-coded miniature hook probe lead set | 1 set | `1000063279.jpg` |
| HW-0151 | Arduino 16×2 LCD Keypad Shield | 1 | `1000063280.jpg` |
| HW-0152 | CTS 208-4 four-way DIP switch | 1 | `1000063285.jpg` |
| HW-0153 | Mini metal slide switch (tentative) | 1 | `1000063285.jpg` |
| HW-0154 | Keyes WiiChuck adapter PCB | 1 | `1000063285.jpg` |
| HW-0155 | Five-color plastic button/joystick caps | 15 (3 each) | `1000063286.jpg` |
| HW-0156 | Standalone two-axis joystick breakout boards | 2 | `1000063288.jpg` |
| HW-0157 | Funduino Joystick Shield v1.A | 1 | `1000063287.jpg` |
| HW-0158 | Red panel-mount pushbuttons with green leads | 4 | `1000063289.jpg` |

**Deduplication:** The two images of HW-0148 show one bundle, not two. HW-0149 is a second bundle. The two joystick modules HW-0156 are independent of the joystick soldered on HW-0157. The yellow 4-bar and green 7-bar LED packages on red foam in `1000063285.jpg` provide supplemental type evidence for HW-0146/HW-0147, **without increasing their 10-each counts** because physical identity to previously photographed parts is uncertain. Earlier female-to-female jumpers HW-0091 remain separate.

**Unverified:** Individual jumper counts and second bundle's exact connector genders, compatibility of button caps, test probe voltage ratings, output type of small slide switch, and working conditions of all devices. The original photo JPGs are referenced but not stored in the repository. [Batch 021 details](batches/2026-11-22-021.md).

## Earlier batch — 020 (5 photographs; 9 new records after owner correction; two distinct red-foam bar-graph lots)

| ID | Item | Count | Photo |
| --- | --- | ---: | --- |
| HW-0146 | Four-bar LED bar-graph modules (red foam; wider/narrower variant) | 10 | `1000063272.jpg` |
| HW-0147 | Seven-bar LED bar-graph modules (red foam; different width) | 10 | `1000063272.jpg` |
| HW-0139 | Clear-lens discrete LEDs | 6 | `1000063276.jpg` |
| HW-0140 | Yellow-lens discrete LEDs | 3 | `1000063276.jpg` |
| HW-0141 | Green-lens discrete LEDs | 5 | `1000063276.jpg` |
| HW-0142 | Red-lens discrete LEDs | ~18 | `1000063276.jpg` |
| HW-0143 | Cylindrical black buzzer / sounder | 1 | `1000063275.jpg` |
| HW-0144 | WS2812 RGB LED breakout modules | 4 | `1000063274.jpg` |
| HW-0145 | Single-digit 7-segment LED displays | 20 | `1000063273.jpg` |

**Owner correction / deduplication:** The red-foam photo is NOT a duplicate of HW-0133. It shows ten four-bar and ten seven-bar packages (20 total), now HW-0146/HW-0147. The earlier ten 10-segment bar graphs stay HW-0133 (10). Total three bar-graph types: 30 packages. Counts of individual LEDs by lens color are 6 clear, 3 yellow, 5 green and approximately 18 red. Clear lens is not evidence of emitted color; buzzer active/passive type and WS2812 revision are unverified. [Batch 020 details](batches/2026-11-22-020.md).

## Earlier batch — 019 (10 photographs; 10 new inventory records)

| ID | Item | Qty | Photograph(s) |
| --- | --- | ---: | --- |
| HW-0129 | Adhesive antenna / RFID-NFC-style stickers (unverified technology) | Unknown | `1000063260.jpg` |
| HW-0130 | 8×8 arrays with individually packaged pixel LEDs — style C | 2 panels | `1000063261.jpg` |
| HW-0131 | Loose bare 8×8 dot-matrix LED displays | 2 confirmed | `1000063262.jpg`, `1000063268.jpg` |
| HW-0132 | MAX7219 8×8 matrix driver module with jumper leads | 1 | `1000063263.jpg` |
| HW-0133 | 10-segment LED bar-graph packages | 10 | `1000063264.jpg` |
| HW-0134 | DIY MORE / DM 4-digit LED modules, plain silkscreen | 2 | `1000063266.jpg` |
| HW-0135 | DIY MORE 4-DigitLED Display modules, title silkscreen | 2 | `1000063266.jpg` |
| HW-0136 | DIY MORE 4-digit breakout with unpopulated header | 1 provisional | `1000063270.jpg` |
| HW-0137 | Miniature red/yellow/green traffic-light breakout | 3 | `1000063269.jpg` |
| HW-0138 | Bare 4-digit seven-segment LED packages | 5 | `1000063271.jpg` |

**Count cautions:** RFID-style sticker count hidden (null). Two bare 8×8 modules confirmed with one possibly repeated close-up. A separate headerless 4-digit board is provisionally counted but could be a rephotograph of an existing 4-digit board. The ten bar graphs, three miniature traffic lights, and five bare four-digit displays are visibly countable. Keep all previous style A/B matrix chains unchanged. [Batch 019 details](batches/2026-11-22-019.md).

## Earlier batch — 018 (9 photos; 9 original records + 1 owner-corrected adapter variant)

| ID | Item | Qty | Uploaded photo(s) |
| --- | --- | --- | --- |
| HW-0119 | Laser-cut brown fiberboard mechanical enclosure / mounting kit (unassembled) | 1 | `1000063259.jpg` |
| HW-0120 | Black USB-A male to square USB-B male adapter (owner-identified) | 1 | `1000063255.jpg`, `1000063258.jpg` (variant unclear) |
| HW-0121 | CanaKit miniature USB Wi-Fi wireless adapter | 1 | `1000063257.jpg` |
| HW-0122 | White two-ended compact USB-family plug adapter (exact connector standards unknown) | 1 | `1000063256.jpg` |
| HW-0123 | 3.7 V 1000 mAh lithium-polymer pouch battery, 523450 marking, bare leads | 1 | `1000063254.jpg` |
| HW-0124 | Lithium-ion polymer rechargeable pouch battery with two-pin connector (capacity unknown) | 1 | `1000063254.jpg` |
| HW-0125 | Two white cabled dual-prong contact / clip assemblies, function unknown | 2 | `1000063253.jpg` |
| HW-0126 | Unbranded nano USB dongle with handwritten 'BT' label (Bluetooth presumed) | 1 | `1000063252.jpg` |
| HW-0127 | IrJACK USB infrared IrDA adapter (lavender) | 1 | `1000063251.jpg` |
| HW-0128 | Black USB-A female to square USB-B male adapter (owner-reported) | 1 | None unambiguously matched |

**Count caveats (owner correction):** **2 distinct black USB adapters**—USB-A male to square USB-B male (HW-0120) and USB-A female to square USB-B male (HW-0128). The two adapter photos cannot be reliably matched to male vs female from the visible angles. Both variants retained separately; the female variant is owner-reported and lacks uniquely verified photographic evidence. There are also 2 distinct Li-ion cells in one photo and 2 white leads in one lot. No electrical testing. [Batch 018 details](batches/2026-11-22-018.md).

## Earlier batch — 017 (10 photos; 10 item records; 2 distinct LED matrix styles)

| ID | Item | Qty | Uploaded photo(s) |
| --- | --- | --- | --- |
| HW-0109 | Servo-driven acrylic robotic arm and gripper | 1 assembly | `1000063235.jpg` |
| HW-0110 | Akai MPD218 MIDI pad controller box (contents unverified) | 1 box | `1000063242.jpg` |
| HW-0111 | Pyle PMIDI100 DJ MIDI controller | 1 device | `1000063243.jpg` |
| HW-0112 | DGT Easy+ timer (owner-confirmed inside box) | 1 timer | `1000063244.jpg` |
| HW-0113 | FUJING USB gooseneck clip-on LED lamp | 1 device | `1000063245.jpg` |
| HW-0114 | 18650 Battery Shield V8.3 (no cells) | 1 module | `1000063246.jpg` |
| HW-0115 | SPI microSD card breakout modules | 2 boards | `1000063247.jpg` |
| HW-0116 | ULN2003 unipolar stepper driver board | 1 board | `1000063248.jpg` |
| HW-0117 | 8×8 LED matrix style A — modular PCBs with intermodule connectors | 2 strips × 4 = 8 matrices | `1000063249.jpg`, `1000063250.jpg` |
| HW-0118 | 8×8 LED matrix style B — continuous-PCB strips | 2 strips × 4 = 8 matrices | `1000063249.jpg`, `1000063250.jpg` |

**Count caveat:** Two distinct LED matrix designs: style A = 2 modular 4-matrix strips (8 matrices), style B = 2 integrated 4-matrix strips (8 matrices). **4 strips and 16 matrices total, unchanged.** Two SPI microSD boards share one inventory record. DGT timer presence in box was confirmed by owner, but not directly photographed; Akai remains packaging-only unconfirmed. No electrical tests performed.

[Batch 017 details](batches/2026-11-22-017.md)

## Earlier batch — 016 (10 photos; 9 top-level objects/sets, 10 records including installed Pi 3)

| ID | Item | Qty | Uploaded photo(s) |
| --- | --- | --- | --- |
| HW-0099 | Microsemi AcuEdge ZLE38AVS voice evaluation platform | 1 assembled platform | `1000063223.jpg`, `1000063225.jpg` |
| HW-0100 | Raspberry Pi 3 Model B, installed in HW-0099 | 1 installed component | `1000063225.jpg` |
| HW-0101 | Silver multimedia / Media Center-style remote | 1 remote | `1000063226.jpg` |
| HW-0102 | DIY neuroscience kit box (contents not seen) | 1 box | `1000063227.jpg` |
| HW-0103 | U-shaped breadboard wire assortment | 1 box / set | `1000063228.jpg` |
| HW-0104 | Morse-code manual straight telegraph key | 1 key | `1000063229.jpg` |
| HW-0105 | Clip-on 0.4× superwide mobile lens | 1 lens + cap | `1000063231.jpg` |
| HW-0106 | Retroflag GPi CASE handheld enclosure | 1 case | `1000063232.jpg` |
| HW-0107 | Multicolor alligator test-lead bundle | 1 bundle | `1000063233.jpg` |
| HW-0108 | Red-and-black test patch-lead bundle | 1 bundle | `1000063234.jpg` |

**Count and identification caveats:** HW-0099/HW-0100 are one assembled AcuEdge platform with an installed Raspberry Pi 3; the closed neuroscience kit HW-0102 is packaging-only; GPi CASE HW-0106 does not prove a Pi Zero is installed. No electrical power-on tests. All photo binaries remain outside GitHub.

[Batch 016 details](batches/2026-11-22-016.md)

## Earlier batch — 015 (10 photos; 7 distinct items)

| ID | Item | Qty | Uploaded photo(s) |
| --- | --- | --- | --- |
| HW-0092 | ET-505 four-pad electrode set | 1 set (4 pads) | `1000063212.jpg` |
| HW-0093 | ASUS Nexus 7 (2013) tablet | 1 | `1000063213.jpg` |
| HW-0094 | Motorola Nexus 6 smartphone | 1 | `1000063214.jpg` |
| HW-0095 | Gold iPhone 8 (probable), shattered glass | 1 | `1000063215.jpg`, `1000063216.jpg` |
| HW-0096 | Orange ZTE Open Firefox OS phone (probable) | 1 | `1000063217.jpg` |
| HW-0097 | LG Nexus 5 (probable), blue case | 1 | `1000063219.jpg`, `1000063220.jpg` |
| HW-0098 | Pandigital digital photo frame, model unknown | 1 | `1000063221.jpg`, `1000063222.jpg` |

**Multiple-view groups:** iPhone `3215/3216`, Nexus 5 `3219/3220`, and Pandigital frame `3221/3222` are each one physical device. Model of iPhone, ZTE and Nexus 5 remain photograph-based and may need label confirmation.

[Batch 015 details](batches/2026-11-22-015.md)

## Earlier batch — 014 (2 photos)

| ID | Item | Qty | Uploaded photo |
| --- | --- | --- | --- |
| HW-0090 | Gray flat IDC ribbon cable, female–female | 1 cable | `1000063210.jpg` |
| HW-0091 | Rainbow Dupont jumper wire bundle, female–female | 1 bundle (wire count unknown) | `1000063211.jpg` |

**Counting:** HW-0090 is one looped IDC cable; HW-0091 is one bundle of jumper wires, individual wire count unverified.

[Batch 014 details](batches/2026-11-22-014.md)

## Earlier batch — 013 (4 photos)

| ID | Item | Qty | Uploaded photo |
| --- | --- | ---: | --- |
| HW-0086 | D01 three-button Bluetooth scrolling ring with charging case | 1 | `1000063209.jpg` |
| HW-0087 | Canon EOS 450D DSLR camera with mounted zoom lens | 1 | `1000063208.jpg` |
| HW-0088 | Canon PowerShot S100 compact digital camera | 1 | `1000063207.jpg` |
| HW-0089 | Canon Digital IXUS 700 compact digital camera | 1 | `1000063206.jpg` |

**Ring note:** HW-0086 is an owner-confirmed **D01** three-button Bluetooth ring with charging case (manufacturer still unknown); it is distinct from the five-button JX-05 ring HW-0046.

[Batch 013 details](batches/2026-11-22-013.md)

## Earlier batch — 012 (6 photos)

| ID | Item | Qty | Uploaded photo |
| --- | --- | ---: | --- |
| HW-0079 | Generic 24 MHz 8-channel USB logic analyzer | 1 | `1000063205.jpg` |
| HW-0080 | Bus Pirate v3a with 3D-printed case | 1 | `1000063204.jpg` |
| HW-0081 | ATtiny2313A-based USB AVR ISP programmer (USBtinyISP-style) | 1 | `1000063203.jpg` |
| HW-0082 | Custom Arduino Nano traffic light training assembly | 1 | `1000063202.jpg` |
| HW-0083 | Arduino Nano installed on traffic-light assembly | 1 | `1000063202.jpg` |
| HW-0084 | Arduino Nano terminal adapter v1.0 | 1 | `1000063201.jpg` |
| HW-0085 | Loose Arduino Nano-compatible boards | 4 | `1000063200.jpg` |

**Arduino Nano quantity:** 5 physical boards (one installed on HW-0082, four loose in HW-0085). HW-0084 is only the screw-terminal adapter.

[Batch 012 details](batches/2026-11-22-012.md)

## Earlier batch — 011 (8 photos)

| ID | Item | Qty | Uploaded photo |
| --- | --- | ---: | --- |
| HW-0071 | Raspberry Pi Pico W | 1 | `1000063199.jpg` |
| HW-0072 | FTDI FT2232H Mini Module | 1 | `1000063198.jpg` |
| HW-0073 | Raspberry Pi Zero 2 W | 1 | `1000063197.jpg` |
| HW-0074 | NE555 multifunction waveform generator module | 1 | `1000063196.jpg` |
| HW-0075 | ESP32-WROOM-32 development board | 1 | `1000063195.jpg` |
| HW-0076 | Raspberry Pi 40-pin GPIO T-cobbler breakout adapter | 1 | `1000063194.jpg` |
| HW-0077 | Smraza Raspberry Pi 4 Model B case kit | 1 | `1000063193.jpg` |
| HW-0078 | DIYmall BBC micro:bit expansion board / edge connector breakout | 1 | `1000063192.jpg` |

**Important:** HW-0077 is a Smraza **case only**, no Raspberry Pi board. HW-0078 is an expansion board, not an additional BBC micro:bit. Other physical development boards have not been duplicated.

[Batch 011 details](batches/2026-11-22-011.md)

## Earlier batch — 010 (10 photographs; 2 owner corrections)

| ID | Item | Quantity | Evidence |
| --- | --- | --- | --- |
| HW-0057 | BBC micro:bit GO box | 1 | Contains HW-0069 confirmed |
| HW-0058 | BBC micro:bit v1.5 | 1 | Physical PCB |
| HW-0059 | BBC micro:bit v1.3B | 1 | Physical PCB |
| HW-0060 | JBL round compact speaker | 1 | Exact model unknown |
| HW-0061 | Arduino Uno-family (FIRMATA-labeled case) | 1 | Actual firmware unverified |
| HW-0062 | Arduino Uno in clear case | 1 | Physical PCB |
| HW-0063 | Arduino Uno loose board | 1 | Third separate Uno |
| HW-0064 | Waveshare ESP32-S3-Touch-AMOLED-1.75-B | 1 | Retail box only; SKU 31262 |
| HW-0065 | LOSER LLC BreadShield v0.4 | 3 | Three separate adapters |
| HW-0066 | Intel Optane Memory M10 32 GB | 1 | Physical M.2 storage module |
| HW-0067 | Avnet Azure Sphere MT3620 Starter Kit 2 | 1 | IoT development PCB |
| HW-0068 | krtkl piSmasher rev 4.1 | 1 | Carrier assembled with HW-0070 |
| HW-0069 | Additional micro:bit in GO kit | 1 | Owner-confirmed, version unknown |
| HW-0070 | Installed krtkl Zynq-7020 FPGA compute board | 1 | Owner-confirmed chipset; exact module SKU unverified |

**BBC micro:bits:** three boards total, one still inside the GO box. **krtkl piSmasher:** populated with a Zynq-7020 FPGA board. The two enclosed/installed boards are modeled as child components, not duplicate machines.

[Batch 010 details](batches/2026-11-22-010.md)

## Earlier batch — 009 (7 photos)

| ID | Item | Quantity | Evidence |
| --- | --- | --- | --- |
| HW-0050 | Clamp-mounted helping hands/magnifier | 1 assembly | Two photos of likely same workstation; exact association tentative |
| HW-0051 | Kester Sn60/Pb40 rosin-core solder, 1 mm | 1 tube | Leaded solder; remaining amount unknown |
| HW-0052 | MG Chemicals 4884-227G Sn63/Pb37, 23 AWG | 1 spool | RA flux 2.2%, labeled 1/2 lb (original nominal quantity) |
| HW-0053 | Hakko digital soldering station | 1 station | FX-888D probable; iron and stand visible |
| HW-0054 | Husky 38-piece stubby socket set | 1 kit | Contents not individually audited |
| HW-0055 | HSC8 6-6 ferrule crimper | 1 tool | Independently usable crimping tool |
| HW-0056 | Blue-handled ratcheting terminal crimper | 1 tool kit | Shares carrying case with HW-0055, bagged accessories |

The clamp and magnifier are *provisionally* one assembly (HW-0050). The final image contains **two different crimping tools**, each with its own record. Both Kester and MG Chemicals solder contain lead, with different Sn/Pb ratios. The Hakko model is only **probably** FX-888D, awaiting nameplate verification.

[Batch 009 evidence](batches/2026-11-22-009.md)

## Earlier batch — 008 (3 photos)

| ID | Item | Quantity | Evidence |
| --- | --- | --- | --- |
| HW-0007 | Ryze Tello drone | 1 drone | Existing item; photographed with 4 prop guards |
| HW-0048 | 2.4 GHz wireless microphone kit | 1 box | Dual-mic package illustration; contents unverified |
| HW-0049 | ATUVOS Apple Find My trackers | 1 box | 4 trackers depicted; actual contents unverified |

The Tello was already cataloged, so **HW-0007** was updated rather than duplicated. The mic and tracker retail boxes do not establish actual contents or functional status. The ATUVOS box depicts four tags, but the number of trackers inside has not been confirmed.

[Batch 008 evidence](batches/2026-11-22-008.md)

## Earlier batch — 007 (5 photos)

| ID | Item | Quantity | Evidence |
| --- | --- | --- | --- |
| HW-0043 | Buddy Paint Art marker | 1 | Marker type/formulation tentative |
| HW-0044 | Spring-loaded desoldering pump | 1 | Tool visible, untested |
| HW-0045 | MG Chemicals 835-P rosin flux pen (10 mL) | 1 | Product label verified; fill remaining unknown |
| HW-0046 | JX-05 Bluetooth ring remote | 1 | Device + instructions visible; pairing untested |
| HW-0047 | Google Daydream View VR headset | 1 box | Packaging only; contents uninspected |

The JX-05 ring controller is a newly recorded device (although previously mentioned in conversation), and the Google Daydream headset is currently verified only through its box. The Buddy Paint Art marker's material is not verified as conductive.

[Batch 007 evidence](batches/2026-11-22-007.md)

## Earlier batch — 006 (10 received / 9 new photos)

| ID | Item | Quantity | Identification |
| --- | --- | --- | --- |
| HW-0034 | Automatic wire stripper / crimper | 1 tool | Range marked 10–24 AWG; tested status unknown |
| HW-0035 | Five-piece precision electronics rework tool set | 1 set / 5 tools | Assorted hook, blade, scraper tips; exact type tentative |
| HW-0036 | Rainbow 40-pin IDC / GPIO ribbon cable | 1 cable | End connections partly obscured |
| HW-0037 | Six-color hookup wire assortment | 1 set | Wire gauge and exact type unknown |
| HW-0038 | DSO112A digital oscilloscope with probe | 1 scope | Label confirmed; untested |
| HW-0039 | Logic-probing test-hook lead bundle | 1 bundle | Exact probe/channel count unknown |
| HW-0040 | TC1 multifunction component tester | 1 device | Different from HW-0015 |
| HW-0041 | JST-style to Dupont jumper-wire bundle | 1 bundle | Pinout/pitch unverified |
| HW-0042 | Miniature hook test clip accessories | 1 bag | Count/type uncertain |

The photo of the AstroAI DM6000AR multimeter is a **repeat of existing HW-0031 / P-20261122-023**, not an additional owned meter. The white TC1 tester HW-0040 is separate from the acrylic-case generic tester HW-0015.

[Batch 006 detailed evidence](batches/2026-11-22-006.md)

## Earlier batch — 005 (8 photos)

| ID | Item | Quantity | Identification |
| --- | --- | --- | --- |
| HW-0026 | Luxonis OpenCV AI Kit (OAK-D probable) | 1 kit | Physical multi-camera board; exact SKU uncertain |
| HW-0027 | Assorted 4-cell battery holders | 9 holders | Mixed size, empty, wires attached |
| HW-0028 | Raspberry Pi in black case | 1 board | Exact board model unknown; hosts Sense HAT |
| HW-0029 | Official Raspberry Pi Sense HAT | 1 HAT | 8×8 RGB LEDs, joystick, environmental/motion sensors |
| HW-0030 | Raspberry Pi in transparent case | 1 board | Exact board model unknown |
| HW-0031 | AstroAI DM6000AR multimeter | 1 | Physically photographed; untested |
| HW-0032 | Raspberry Pi Camera V2, 8MP | 1 box | Package only; module uninspected |
| HW-0033 | Iomega Zip 250 USB drive | 1 | Physical device with cable; untested |

The **official Sense HAT HW-0029** is fitted to **Raspberry Pi HW-0028**. Another board **HW-0030** is in a fully transparent case. Exact Pi model numbers are unconfirmed until silkscreen or `cat /proc/device-tree/model` can be read; neither unit is presumed to be a previously inventoried Pi.

[Batch 005 detailed evidence](batches/2026-11-22-005.md)

## Earlier batch — 004 (5 photos)

| ID | Item | Quantity | Evidence |
| --- | --- | --- | --- |
| HW-0004 | Kria KV260 Vision AI Starter Kit | 1 package | Previously recorded; package only |
| HW-0021 | TUL PYNQ-Z2 Zynq FPGA development kit | 1 package | Box only; board contents unchecked |
| HW-0022 | Unbranded Wi-Fi HD video camera | 1 package | Front and back of same box; camera unseen |
| HW-0023 | Medium solderless breadboard (~400 points) | 1 | Hardware directly photographed |
| HW-0024 | Full-size solderless breadboard (~830 points) | 1 | Hardware directly photographed |
| HW-0025 | YwRobot breadboard power supply module | 1 | Hardware directly photographed, untested |

**Key deduplication:** The Xilinx Kria KV260 was already in HW-0004 and was updated rather than added. Two photos of the same Wi-Fi camera box share HW-0022. The small breadboard and attached YwRobot module are separately reusable, so HW-0023 and HW-0025 have different IDs.

[Batch 004 evidence notes](batches/2026-11-22-004.md)

## Earlier batch — 003

| ID | Item | Status |
| --- | --- | --- |
| HW-0018 | New Retroflag SUPERPi CASE Deluxe Edition | Empty case; separate from HW-0016, owner-confirmed |
| HW-0019 | White/red Raspberry Pi case | Empty case, owner-confirmed |
| HW-0020 | 18 W adjustable universal AC/DC adapter with tips | Device photographed; settings and output untested |

The existing SUPERPi retro-gaming system HW-0016 is **not** the same case as the new empty Deluxe Edition case HW-0018.

[Batch 003 notes](batches/2026-11-22-003.md)

## Earlier batch — 002

| ID | Item | Evidence |
| --- | --- | --- |
| HW-0006 | Google AIY Vision Kit | Retail box only; included Raspberry Pi uninspected |
| HW-0014 | Intel Neural Compute Stick 2 | Retail box only; stick uninspected |
| HW-0001 | Raspberry Pi 4 Model B, 2 GB RAM | Owner checked physical board inside box |
| HW-0015 | LCD component tester | Device photographed, untested |
| HW-0016 | Retroflag SUPERPi retro-gaming system | Pi 3 Model B (tentative), 1 GB RAM, owner-reported |
| HW-0017 | NXP Rapid IoT Prototyping Kit | Retail box only |

[Batch 002 notes](batches/2026-11-22-002.md)

## Earlier batch — 001

| ID | Item | Evidence |
| --- | --- | --- |
| HW-0011 | 4WD acrylic robot chassis | Visible assembled mechanical kit |
| HW-0012 | Quartz analog clock movement | Component directly photographed |
| HW-0013 | Conductive tape for paper circuits | Owner-confirmed function; photographed roll |

[Batch 001 notes](batches/2026-11-22-001.md)

## Previously reported, awaiting photos

| ID | Item |
| --- | --- |
| HW-0002 | Raspberry Pi 5 |
| HW-0003 | Coral USB Accelerator |
| HW-0005 | AIY Voice Kit |
| HW-0007 | Tello drone |
| HW-0008 | Flight joystick |
| HW-0009 | Nest doorbell |
| HW-0010 | Nest Wi-Fi camera |

## Records and photo references

[Canonical hardware inventory](items.json) · [Photo evidence log](../intake/photos.json)

Original image binaries are conversation attachments, **not yet stored in GitHub**. The log links filenames and photo IDs to hardware records. Conditions remain unknown unless tested or confirmed by the owner.
