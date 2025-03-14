# VS.912 | Switchwire
My Ender 3 to Switchwire conversion

![enderwire](https://github.com/CobreDev/Switchwire/blob/main/klipper-backup/images/enderwire.jpg)

## The Build
This is almost completely based off of [EzrielDreamurr's Ender 3 Pro/V2 Switchwire conversion](https://github.com/EzrielDreamurr/Voron-Ender_3Pro_Switchwire) (V1). I'm using skirts from [DaRk_dOg's conversion](https://github.com/boubounokefalos/Ender_SW/), but mostly because I had them printed already and didn't need to reprint them.

### Filament:
Orange: Hatchbox ABS<br>
Black: Sunlu ABS<br>
(basically whatever was cheap on Amazon when I bought filament)

### Electronics:
This printer is running a BTT Manta M5P with a BTT CB2 for the host. This is a great all-in-one solution with a pretty low footprint.
I'm also running an EBB36 CANbus board on my toolhead, connected to the M5P directly.

### Toolhead:
I recently switched from the stock Voron Stealthburner/Clockwork 2 toolhead, to  KevinAkaSam's [Papilio](https://kevinakasam.com/papilio/) belted extruder with an [A4T](https://github.com/Armchair-Heavy-Industries/A4T/) toolhead. For a hotend I'm using a TZ V6 2.0, which is a fantastic budget hotend that can use regular V6 nozzles.

### Modifications:
- [Front Grill with Fan](https://www.printables.com/model/1124643-enderwire-front-grill-with-fan)
  - I have my BTT Pi at the front of the electronics bay, so a rear mounted fan was pretty useless. I modified the front grill to be able to fit a fan to keep the Pi cool
- [FT EMS](https://www.printables.com/model/491106-ft-ems-swc-ender-3-v2pro-electronics-management-sy) with relevant [mounts](https://www.printables.com/model/558357-ft-ems-mounts-repository)
  - In the past I've used DIN rails which worked for the most part, but this gives me the most flexibility. I'm happy with it so far!
- [Logitech C920 Camera Mount](https://www.printables.com/model/476253-c920-logitech-camera-mount-3d-printer-mount-can-be)
  - I'm using a [longer spacer arm](https://www.printables.com/model/1220410-c92x-longer-spacer-arm) so that the camera is in the right location
- [Bed Cable Strain Relief](https://www.printables.com/model/212186-ender-3-pro-90deg-heated-bed-cable-strain-relief)
