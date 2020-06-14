# Web-Radio
Web Radio with ESP32

PCB for Web Radio based on the popular ESP32 mcrocontroller.
Dimensions: 80 x 80 mm

Bill of Material
If a component is not available from a seller, try another seller that offers the same components.

Where to find the components for the webradio on AliExpress:

1 x PAM8403 5V DC Audio Amplifier Board
The switch in the potmeter of the PAM switches the power to the radio on and off.

1 x ESP32 Development Board

1 x VS1053 MP3 Module Development Board

1 x 1.8 Inch 128*160 Serial SPI TFT LCD Module Display

2 x 1300:8 Ohm Audio Transformer
The transformers have a primary and secundary side.
One side has a small dot (see photos).
Place the transformer on the pcb and align the dots.

2 x 2.54mm 2PIN Pin Male & Female PCB Connector JST (for 2 speakers)

1 x 2.54mm 8PIN Pin Male & Female PCB Connector JST (for display)

2 x speaker
You can also use 5W 8 ohm speakers.

4 x push button (optional)

Tips:
If you only use the web interface to control the radio you don't need the push buttons.
The PCB uses GPIO 16 for the DCS pin of the VS1053, so set this accordingly in defaultprefs.h:
pin_vs_dcs = 16 # GPIO Pin number for VS1053 "DCS"
Also, use the config page of the webinterface to change settings including pin_vs_dcs.

You can buy the PCB on my website http://nakedninja.cc.
 
Specifications:

Microcontroller: ESP32 (M5Stack Basic Core)
- Flash Memory: 4MB
- RAM: 520kB
- Clock Speed: 240MHz
- Operating Voltage: 3.3/ 5 Volt
Power Supply Voltage: 5 Volt
Operating Current:
- Standby mode: 160~260 mA
- Active mode:     400~700 mA
Audio Codec: VS1003/1053
Stereo Audio Booster: PAM8403

 
