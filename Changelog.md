## V1E2
- Added mic recording
- Baud rate change bugfix
- Neopixel support (Serial RGB pin)
- Other bugfix
## V1E1
- Position full scale configuration didnt' work
- Proximity managed event not set correctly if a configure command different from 1 is sent before
- Led mask not working with managed events
- Led change mode not working with some parameters
- Long prox disabling not working
- Random parsing error due to missing var initialization
- Soft reset command didn't clear some sensor correctly
- Added notification frequency configuration for enviroment sensors
## V1
- Added soft reset to clear every command without rebooting
- Various fix for proximity and lux reading
- Fix microphones disabling prox/lux mems
- Fix message loss
- Added gestures support
- Led commands now allow bit mask
- Integrated managed led commands to handle effects easily
- Gyro and accellerometer scale can now be configured
- Added 20 seconds delay before rebooting the system with "START FIRMWARE UPGRADE" and "RESET" command 