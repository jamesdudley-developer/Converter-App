# Field Instrument Converter v4.2

Offline-first PWA for field instrumentation, electrical and PLC troubleshooting calculations.

## Main tools
- Pressure (incl. hPa), length/level, flow, weight and temperature conversion
- 4–20 mA engineering-unit scaling
- DP flow with square-root extraction
- Cylinder/tank volume
- Radar level and tank volume
- Force and pressure/force/area
- Ohm’s law
- Single- and three-phase power with power factor
- DC/single-phase and three-phase voltage drop
- Mass/density/volume
- Error calculator: standard error (measured − reference, % of reading) and error as % of span, with 4–20 mA output; tolerance pass/fail as ± % of reference (standard) or ± % of span
- Engineering calculator with parentheses, powers, square and square root
- Decimal/binary/hexadecimal conversion using arbitrary-size integers

## PLC / instrumentation toolbox
- 8/16/32-bit signed/unsigned word conversion
- Binary / decimal / hexadecimal representation
- Bit read, set, clear and toggle
- Bit numbering with bit 0 as LSB
- IEEE-754 32-bit floating-point ↔ hexadecimal conversion
- IEEE byte/word ordering: ABCD, BADC, CDAB, DCBA
- Modbus 16-bit register conversion
- Modbus 32-bit / two-register conversion with byte/word ordering
- Signed and unsigned 16/32-bit interpretation
- 4–20 mA diagnostic interpretation including a NAMUR NE43-style range display

## Navigation
Tools are grouped into five cards (Units, Instrumentation, Process, Electrical, Tools); only the selected group's tools are shown.

## Saved values
The last-used tab and every value/unit in each tab are saved on the device and restored when the app reopens.

## Themes
Blue, Green, Orange and Slate themes are available and saved locally on the device.

## Deployment
Serve the folder over HTTPS. For local development, `http://localhost` is suitable for service-worker/PWA testing.

## Local HTML test
Open `field-instrument-converter-v4-test.html` directly in a browser for calculation/UI testing. Service-worker registration and install prompting are disabled in that file.

## Files
- `index.html` — production PWA application
- `field-instrument-converter-v4-test.html` — standalone local test page
- `manifest.json` — PWA metadata
- `service-worker.js` — offline cache
- `icons/` — application icons
