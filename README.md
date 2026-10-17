**fltDashP3 & fltDashP3v2  — EdgeTX Flight Dashboard Widget**

Both dashboards are a modern telemetry and flight dashboard widgets for EdgeTX 2.11+, designed for radios with larger colour displays such as the Radiomaster TX16S & GX15.

The dashboard provides a compact view of the most important flight and model information, combining telemetry, battery status, throttle, aircraft configuration and a model-specific image into a single screen.
The layout is dynamically sized using the available widget dimensions, allowing it to adapt to different screen heights while maintaining the same 480-pixel-wide layout.

**Features**
- RSSI / Signal — 5-bar signal indicator with dynamic bar levels and green, yellow, red and no-signal colour states.
- Receiver Battery — Displays receiver voltage, calculated cell voltage, battery percentage and colour-coded battery level.
- Capacity — Displays consumed mAh, configurable maximum capacity and a visual capacity indicator.
- Model Image — Automatically loads the image matching the current model name from the /IMAGES/ folder and scales it while maintaining aspect ratio.
- Altitude — Displays current altitude and the recorded maximum altitude using the EdgeTX Alt+ telemetry value.
- GPS — Displays GPS telemetry information with a dedicated satellite icon.
- Flight Timer — Displays the model's primary EdgeTX flight timer.
- Motor Status — Displays motor ON/OFF status with a dedicated motor icon.
- Landing Gear — Displays landing gear UP/DOWN status with dedicated gear and directional arrow icons.
- Flaps — Displays flap position for three-position configurations: UP, MID and FULL.
- Throttle — CH3-based throttle percentage with an 8-segment colour-coded throttle bar and custom throttle graphic.
- Dashboard Layout — Dark gradient background, cyan telemetry styling, chamfered panels and a compact multi-column layout.
- Dynamic Layout — Uses the available widget dimensions to accommodate different screen heights while maintaining the 480-pixel-wide design.
- Configurable Telemetry Sources — GPS, altitude, RSSI, receiver battery and capacity sources can be assigned through widget settings.
- Configurable Switches — Motor, landing gear and flap switches can be assigned through widget settings.

**What's Different in fltDashP3 V2?**
- Current replaces Altitude — Displays current draw in amps.
- Rearranged Layout — Model, RSSI and GPS are displayed in the top bar.
- Middle Column — RxBat, Capa and Flight Timer, each with its own icon.
- Same Core Features — Model image, throttle bar, motor, landing gear and flap indicators retained.

**Compatibility**
- EdgeTX 2.11+
- Designed for colour LCD radios
- Optimised around a 480-pixel-wide display
- Layout uses the widget's available dimensions to accommodate different screen heights
- Tested on the Radiomaster TX16S MK2, GX15 & TX15
