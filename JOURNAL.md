
## Part Selection

Did some research on parts, and settled on using 2 EC11s, a 0.96 in OLED screen, one momentary push button, and a SPST switch for navigation and controlling leds. I'm using a ESP32C3 Mini to run the hub. I'm using two JST connectors for LED wires, as well as a terminal block if they are stripped. So far the project is looking good, and seems feasable.

<img width="1470" height="802" alt="Screenshot 2026-11-06 at 8 28 56 PM" src="https://github.com/user-attachments/assets/cddf9c31-4f8f-4a3b-8afd-4115b1849678" />

**Total time spent: 1h 30m**

## Installed easyDA to Kicad

I was trying to find a specific oled screen symbol for maybe 30 minutes before finding the easyDa to kicad code terminal thingy, and then I installed and used it to add all symbols.

<img width="1470" height="882" alt="Screenshot 2026-11-09 at 11 02 14 AM" src="https://github.com/user-attachments/assets/ba203671-d105-41c6-bf74-6a8a784a7d47" />

**Total time spent: 1h**

## Finished schematic.

Connected everything and changed my mind about using an esp32 and switched to arduino nano. For some reason I decided to use the green wire things, but then it got super unorganized so I switched to labels.

<img width="481" height="302" alt="Screenshot 2026-11-09 at 10 57 50 AM" src="https://github.com/user-attachments/assets/2c71684b-e4df-4023-b82c-155cf9d4a0cf" />

**Total time spent: 1h**

## Placed all pcb components.

I spent maybe 20 minutes moving all the parts around before settling on having the nano, , rotary encoder, button, switch, barrel jack, and screen on the top, and having all the inputs at the bottom.

<img width="775" height="466" alt="Screenshot 2026-11-09 at 11 10 48 AM" src="https://github.com/user-attachments/assets/63d3f835-0ef5-485b-b97c-d0cf502f623a" />

**Total time spent: 20 m**

## Routed everything.

I started with doing a ground fill on top and tried to do a one sided pcb, but then I gave up because routing was making my brain hurt, so I switched to putting all the power and gnd stuff on the front side, and all the data wiring on the back side. I made the pcb so all the pins are on one side except for sda and scl, and I made data tracks 0.4mm thick, and power tracks 1 mm thick. 

<img width="991" height="560" alt="Screenshot 2026-11-09 at 11 07 52 AM" src="https://github.com/user-attachments/assets/40a0a426-20c2-4d36-91f9-ee93e76d00bf" />

**Total time spent: 1h 30m**

## Downloaded and added 3d models.

I used grabcad to get all the 3d models I needed, and then moved the models around so they fit into the pins. It looks great, moving to case design.

<img width="1181" height="660" alt="Screenshot 2026-11-09 at 1 04 45 PM" src="https://github.com/user-attachments/assets/4b4d7d02-b2ae-44ea-9b4e-0049500a2a74" />

**Total time spent: 1h 10m**

