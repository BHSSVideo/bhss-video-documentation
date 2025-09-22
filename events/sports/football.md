# Football
## Top of Press Box 
- Camera 1
- Camera 2
- Camera Mounting Hardware
    - 1/4"-20 Screws (Standard Tripod Screws)  
    - Brackets (if not already installed)
    - Metal Zip Ties
    - Vibration Dampening
        - rubber pads??
- Ladder
## In the Press Box
### Announcer Area
- 2x XLR Cable (M->F)
    - must be long enough to reach the main mixer
- Laptop Charger - barrel plug
- Ethernet adapter
- Announcer Laptop
- Audio Interface (Audient EVO 8)
- Cardioid XLR Microphone
- Headphones (connects via TRS)
- 10' Ethernet Cable
- USB-C Cable (C<->C)
- 3.5mm to XLR cable
- DJI Microphones (charged)
### Scoreboard Area
- Scorebug Computer
- Laptop Charger
- Serial -> USB-A Cable
- 10' Ethernet Cable

# Software Setup
## Streaming PC configuration
In an ideal situation OBS on the streaming PC will be configured with 4 different scense for footbal 2 of which are optional the scense are as follows
the formatting is as follows the sources should be in the same order as listed.
### Scence Name
 - First source name 
 - Second Source name
 - Third Source name 
     - Details about how this source is to be configured

### Camera 1 - Name of operator
 - NDI Camera 1
     - Source Name: Camera 1
     - Behavoir: Always Play when not visible
     - Bandwith: Highest
     - Audio/Video Sync: network
     - Framesync: Enabled
     - Request Hardware Acceleration: Enabled
     - Latency Mode: Normal Safe
     - Filters to apply to the source:
         - (LVK) Video Stabilizer
