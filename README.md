**fltDashP3 & fltDashP3v2  — EdgeTX Flight Dashboard Widget**

Both dashboards are a modern telemetry and flight dashboard widgets for EdgeTX 2.11+, designed for radios with larger colour displays such as the Radiomaster TX16S & GX15.

The dashboard provides a compact view of the most important flight and model information, combining telemetry, battery status, throttle, aircraft configuration and a model-specific image into a single screen.
The layout is dynamically sized using the available widget dimensions, allowing it to adapt to different screen heights while maintaining the same 480-pixel-wide layout.

**Project Background**

_This project started when Kamil Poslada asked on a Facebook group if anyone could create an EdgeTX telemetry dashboard for the RadioMaster GX15. I volunteered to take on the challenge, using his AI-generated image I recreate the design as a fully functional EdgeTX dashboard widget._

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

**What's Different in fltDashP3v2?**
- Current replaces Altitude — Displays current draw in amps.
- Rearranged Layout — Model, RSSI and GPS are displayed in the top bar.
- Middle Column — RxBat, Capa and Flight Timer, each with its own icon.
- Same Core Features — Model image, throttle bar, motor, landing gear and flap indicators retained.

**What's Different in fltDashP3vh?**

fltDashP3vh builds on the original dashboard while introducing helicopter-specific features.

- RPM Display — Replaces the throttle bar with a configurable telemetry RPM reading, making rotor speed information easy to see at a glance.
- ARM Status — Replaces the Landing Gear panel with an ARM status indicator. A custom power-button icon changes colour depending on whether ARM is ON or OFF.
- ESC Temperature — Replaces the Flaps panel with a configurable ESC temperature reading displayed in degrees Celsius, alongside a custom thermometer icon.
- Flight Bank Indicator — Displays the current flight bank in the top information bar, making it easy to identify the active flight mode at a glance.
- TX Battery Warning Indicator — Adds a small coloured circle inside the RxBat panel to monitor transmitter battery voltage:
  - Green: Above 7.3V
  - Orange: From 6.8V up to and including 7.3V
  - Flashing Red: At or below 6.8V
- Custom Icons — Adds dedicated icons for ARM status and ESC temperature, matching the dashboard's visual style.
- Responsive Layout — Uses the widget's available screen dimensions to position and size its panels, helping the dashboard adapt to different transmitter screen resolutions.

**Compatibility**
- EdgeTX 2.11+
- Designed for colour LCD radios
- Optimised around a 480-pixel-wide display
- Layout uses the widget's available dimensions to accommodate different screen heights
- Tested on the Radiomaster TX16S MK2, GX15 & TX15

**Installation & Setup**
- Download the ZIP file
- Extract the contents of the ZIP file
- Locate the last folder named fltDashP3 or fltDashP3v2 (it contains main.lua)
- Copy this fltDashP3 or fltDashP3v2 folder only
- Paste the folder into your SDCard/WIDGETS folder
- Use the Widget Options to assign the telemetry and switches
- Save your model image as a .png file in the SDCard/IMAGES/ folder, using the exact model name, including matching capitalisation.

**Images**

fltDashP3

<img width="491" height="278" alt="image" src="https://github.com/user-attachments/assets/3811a21f-c0bd-4baa-97fc-bd4f1dee1e76" />

fltDashP3v2

<img width="501" height="289" alt="image" src="https://github.com/user-attachments/assets/f5a2bc56-423c-4e22-a81a-98371d36c4ae" />

fltDashP3vh

<img width="485" height="279" alt="image" src="https://github.com/user-attachments/assets/501a0d3a-77f8-4080-91c7-1de647d87494" />

AI-Generated Design of this telemetry dashboard

<img width="790" height="356" alt="image" src="https://github.com/user-attachments/assets/a098b53e-68b4-491b-8f50-dcc43682c3cd" />



