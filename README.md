# Atlas - VS.912
My Ender 3 to Switchwire conversion

## The Build
This is almost completely based off of [EzrielDreamurr's Ender 3 Pro/V2 Switchwire conversion](https://github.com/EzrielDreamurr/Voron-Ender_3Pro_Switchwire) (V1). I'm using skirts from [DaRk_dOg's conversion](https://github.com/boubounokefalos/Ender_SW/), but mostly because I had them printed already and didn't need to reprint them.

### Filament:
Orange: Hatchbox ABS<br>
Black: Sunlu ABS<br>
(basically whatever was cheap on Amazon when I bought filament)

### Electronics:
For the Klipper host, I'm using a BTT Pi v1.2. This is very handy because it can be powered directly off of 24v, unlike a regular Raspberry Pi which requires 5v.<br>
My main MCU is a BTT SKR Mini E3V3. This board has a pretty small footprint, but still has a lot of i/o.<br>
I'm also running an EBB36 CANbus board on my toolhead, connected to the BTT Pi through a BTT U2C.

### Toolhead:
For now I'm using the stock Voron Stealthburner toolhead, with the Clockwork 2 extruder. I do however plan to try out KevinAkaSam's [Papilio](https://kevinakasam.com/papilio/) belted extruder soon, as my cheap knockoff BMG gears are causing slight layer inconsistency. <br>
My hotend is a Bambu Labs hotend, which I've been happy with. It's cheap, and performs well. I'm using [this printhead mount](https://www.printables.com/model/497742-bambu-hotend-stealthburner-printhead) to put that in the Stealthburner.

### Modifications:
- [Front Grill with Fan](https://www.printables.com/model/1124643-enderwire-front-grill-with-fan)
  - I have my BTT Pi at the front of the electronics bay, so a rear mounted fan was pretty useless. I modified the front grill to be able to fit a fan to keep the Pi cool
- [FT EMS](https://www.printables.com/model/491106-ft-ems-swc-ender-3-v2pro-electronics-management-sy) with relevant [mounts](https://www.printables.com/model/558357-ft-ems-mounts-repository)
  - In the past I've used DIN rails which worked for the most part, but this gives me the most flexibility. I'm happy with it so far!
