# How-tows

## Dev Setup

1. Plug-in power supply to the wall
1. Connect power supply to the power switch board
1. Connect power switch board to printer control board
1. Check X/Y/Z stopper switches
1. Turn on power supply
1. Make sure power switch board red LED is lit
1. Turn on power switch board
1. Make sure printer LET display is on with Marlin logos and stuff
1. Make sure laptop is running on power supply (grounded)
1. Connect printer control board to laptop with USB

## How to burn new Marlin image/config

1. Finish the "Dev Setup"
1. In PIO, select mega2560 as the board
1. Build
1. Upload

## Print Setup

- Reset X/Y position
  - Currently the X/Y stopper is not fixed on to the platform and has too much give. We need to manually set it to near zero upon start
- Make sure metal z rod is screwed into the rod holder tightly

## Todos

- [x] verify x/y axis steps-per-unit setting
- [x] adjust z axis steps-per-unit setting
- [x] set up glass print bed again
- [ ] hook up fillament and test hot nozzle
- [ ] print new hot bed holder
- [ ] set up hot bed
  - [ ] enable hot bed temp sensor
- [ ] print new z stopper holder
- [ ] print new x stopper and motor holder
- [ ] print new y stopper and motor holder
- [ ] print more chain links to hold cables
- [ ] lube the metal z rod
