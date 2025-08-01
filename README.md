# bagel24

A printer designed in 24 hours.

![alt text](pictures/the-machine.png)

(the 24 is for 24 hours, not a voron reference)

# but why?

Long story short, I didn't realize I still had time to submit things to Hack Clubs Highway event--until I had almost exactly 24 hours left. So, I made this. Its a combination of a custom frame, Monolith gantry, and Xol toolhead with a Bambulabs X1C hotend, capable of using the A1 Mini build plate.

### [CAD IS HERE](https://cad.onshape.com/documents/a25eb3393e530945c6474152/w/d83d10951cb1e8008c7f68e6/e/854bc744f46243b389612f55?renderMode=0&uiState=688c1bc2fb56dc36b3a2ea53)

# the bom

| PART                         | UNIT COST | QUANTITY | SPONSORED? | NOTES                                                                                 | ROW COST | SOURCE                                                                                                                                                                 |
| ---------------------------- | --------- | -------- | ---------- | ------------------------------------------------------------------------------------- | -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| T8x4 Leadscrew 250mm         | $10.95    | 3        | FALSE      |                                                                                       | $32.85   | [Link](https://www.aliexpress.us/item/3256806551253663.html)                                                                                                           |
| MGN9H 250mm Linear Rail      | $9.97     | 3        | FALSE      |                                                                                       | $29.91   | [Link](https://limobearing.com/mgn9c-mgn9h-miniature-linear-guideway)                                                                                                  |
| MGN9H 240mm Linear Rail      | $9.97     | 2        | FALSE      |                                                                                       | $19.94   | [Link](https://limobearing.com/mgn9c-mgn9h-miniature-linear-guideway)                                                                                                  |
| MGN12H 240mm Linear Rail     | $10.71    | 1        | FALSE      |                                                                                       | $10.71   | [Link](https://limobearing.com/mgn12c-mgn12h-mini-linear-sliding-rail)                                                                                                 |
| 42mm Nema 17 Stepper Motor   | $4.72     | 5        | TRUE       | LDO Sponsorship                                                                       | $0.00    | [Link](https://www.omc-stepperonline.com/e-series-nema-17-bipolar-42ncm-59-49oz-in-1-5a-42x42x38mm-4-wires-w-1m-cable-connector-17he15-1504s)                          |
| Sherpa Mini                  | $25.75    | 1        | FALSE      |                                                                                       | $25.75   | [Link](https://www.aliexpress.us/item/3256808907879339.html)                                                                                                           |
| Extruder Motor               | $18.30    | 1        | TRUE       | LDO Sponsorship                                                                       | $0.00    | [Link](https://biqu.equipment/products/biqu-orbiter-v1-5-extruder-dual-driver-gear-extrusion-3d-printer-parts-for-cr10-10s-ender3-3-pro-ender5?variant=40041793683554) |
| BTT EBB36                    | $9.40     | 1        | FALSE      |                                                                                       | $9.40    | [Link](https://www.aliexpress.us/item/3256804056513768.html)                                                                                                           |
| 350mm Extrusion              | $7.72     | 11       |            | I'll be trying to get an extrusion sponsor but I doubt it will be possible.           | $84.92   | [Link](https://www.aliexpress.us/item/3256802466647592.html)                                                                                                           |
| 300mm Extrusion              | $6.99     | 2        |            |                                                                                       | $13.98   | [Link](https://www.aliexpress.us/item/3256802466647592.html)                                                                                                           |
| 200mm Extrusion              | $5.31     | 1        |            |                                                                                       | $5.31    | [Link](https://www.aliexpress.us/item/3256802466647592.html)                                                                                                           |
| 450mm Extrusion              | $9.67     | 4        |            |                                                                                       | $38.68   | [Link](https://www.aliexpress.us/item/3256802466647592.html)                                                                                                           |
| X1C Hotend                   | $26.18    | 1        | FALSE      |                                                                                       | $26.18   | [Link](https://www.aliexpress.us/item/3256806847064566.html)                                                                                                           |
| GT2 6mm Belt 1240mm Belt     | $9.94     | 1        |            |                                                                                       | $9.94    | [Link](https://www.aliexpress.us/item/3256805605215455.html)                                                                                                           |
| 4010 Fan                     | $9.72     | 2        | FALSE      |                                                                                       | $19.44   | [Link](https://www.aliexpress.us/item/3256808672138365.html)                                                                                                           |
| PEI Plate and Magnet         | $26.76    | 1        | FALSE      |                                                                                       | $26.76   | [Link](https://www.aliexpress.us/item/3256809109559068.html)                                                                                                           |
|                              |           |          |            |                                                                                       | $0.00    |                                                                                                                                                                        |
| Mainboard                    | $0.00     | 1        | TRUE       | I'll be asking many companies for a sponsorship or using 2 of the ones I already own. | $0.00    |                                                                                                                                                                        |
| Screws, nuts, pulleys, etc   | $0.00     | 0        | TRUE       | I own it already or will pay out of pocket                                            |          |                                                                                                                                                                        |
| Filament                     | $0.00     | A lot    | TRUE       | Polymaker should be sponsoring with ASA                                               |          |                                                                                                                                                                        |
| Bed                          | $17.19    |          |            | Potentially will get sponsored by PCBWAY or pay out of pocket                         |          | JLCCNC                                                                                                                                                                 |
| 10 pack of 1m 2020 extrusion | $44.01    | 1        |            | I'll buy this instead of the above extrusion if I can get the welcome deal.           |          | [Link](https://www.aliexpress.us/item/3256807024011071.html)                                                                                                           |

The overall cost is $353.77. This does not include the steppers, as I already have most of them and can get many sponsored to me. If LDO is kind enough, I'll make an AWD version of this, if I have a mainboard for it.

# wiring diagram

![alt text](pictures/wiring.png)

# Credits

Thanks to the Voron team for publishing their kinematic Z mounts under the GPL license as part of the Voron Trident. This machine drew a lot of inspiration from the way the bed was used on the Trident.

[The Monolith gantry by CloakedWayne](https://github.com/CloakedWayne/Monolith_Gantry_V2-VT) is used in this machine
