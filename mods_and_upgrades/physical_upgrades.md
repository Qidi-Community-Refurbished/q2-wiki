# List of Physical Upgrades

A running catalog of physical upgrade parts for the Q2, grouped by area. Each entry lists the recommended option(s) and any relevant background.

## Cooling

### Part Cooling Fan

The stock part cooling fan is not very good, especially if you do a lot of PLA or PETG printing. There are a few different upgrade options available. For users in the US, the R3men fan is generally considered the best option. The [R3men 5015 Wide Mouth 4-Pin](https://www.r3men.com/products/5015-wide-outlet-blower-fan-2-pin-r3-fan?variant=48281912180979) is plug-and-play — no crimping or soldering is required.

European users — input needed.

Sakarnen on the Qidi Discord has detailed information on the options: there's 4 r3men fans that can fit the Q2: 4 pin narrow, 2 pin narrow, 4 pin wide, and 2 pin wide.

The narrow mouth fans don't have the right connector to fit the toolhead board, but you can solder, splice, or re-crimp the correct connector onto them (4 pin PH 2.0 or 2 pin XH 2.54 are the correct JST connectors). The wide mouth ones will both plug into the board without modification.

4 pin fits the stock cooling fan port. 2 pin fits the unused FAN2 port, and you just have to copy and paste in a config change to printer.cfg to make it work.

The 2 pin fans have a bit more airflow than the 4 pin IIRC — slightly higher RPM. The narrow mouth fans have higher airflow than the wide mouth, but the flow from the wide mouth is more balanced.

IMO you want to use a 4 pin, because then the 2 pin port is still available for a hotend fan upgrade — it is very difficult to find a 4 wire hotend fan that can use the stock hotend fan port.

### Part Cooling Duct

Similar to the part cooling fan, the stock cooling duct is not particularly effective. The [Dual Flow Cooling Duct](https://www.printables.com/model/1642251-qidi-q2-cooling-duct-v51-v60-dual-flow) is a good replacement — from what I've heard, the best options are the 5.1 and 6.0 versions. Be sure to orient the print as shown in the 11th picture and follow all other recommended print settings.

You can print this in ABS if necessary, but it will not last forever, especially when printing high-temperature materials. Common choices are ABS-GF, PET-GF, and nylon-based materials.

### Auxiliary Cooling Fan

Almost nobody upgrades this. Just turn it off.

### Hotend Fan

The [HoneyBadger 2510 (2-Pin or 3-Pin)](https://www.fabreeko.com/products/2510-performance-axial-fan-by-honeybadger) is a plug-and-play hotend fan upgrade. Some users (such as Sakarnen) print PLA with 50°C chamber temperatures using this fan to reduce warping and improve layer adhesion.

The [HoneyBadger 3010](https://www.fabreeko.com/products/3010-performance-axial-fan?_pos=1&_sid=16984af0c&_ss=r) is another plug-and-play hotend fan upgrade. The stock toolhead cover cannot be used with this fan.

The [Lightweight Hotend Fan Bracket](https://www.fabreeko.com/products/3010-performance-axial-fan?_pos=1&_sid=16984af0c&_ss=r) is a lightweight bracket designed for both the 2510 and 3010 fans. This bracket is required when using the 3010 fan.

## Heating

### Graphite Bed

The [Graphite Bed](https://www.r3men.com/products/graphite-heated-bed-for-qidi-q2) has advertised benefits including faster heating, reduced warping, and lower weight.

Personal feedback on installation difficulty, long-term durability, and overall usefulness is still needed.

The [Build Sheet Guides](https://www.printables.com/model/1621483-qidi-q2-r3men-graphite-bed-corner-guides) are alignment guides designed for use with the R3men graphite bed.

### Conch Nozzle System

Conch (nozzle) — "Releasing Q3". There is currently no confirmed release date, but it is expected to adapt commonly used V6 nozzles for use on the Q2.

## TPU & Other Flexibles

### Top-Mounted Spool Holder

The [Top Mount Spool Holder](https://odysee.com/@The_Mi3_Channel:f/Q2-Flexibles-Top-Spool-Holder:a) places the spool directly above the printer to reduce feeding resistance and help prevent TPU feeding issues.

### Extruder Shim

The [Extruder Shim](https://www.printables.com/model/1491712-qidi-q2-tpu-fixer) removes excess space inside the extruder path and helps prevent flexible filaments from feeding where they should not.
