Revamped-DRM127-Ventilator-PCB
==============================

This is an Altium version of the popular NXP (Freescale) ventilator design
note, DRM127 which was printed in 2010. A lot of groups have been looking
into building the NXP design in view of the Covid-19 pandemic. Unfortunately,
pressure sensors are quite difficult to get as a result.

Please note the component designators are not the same as the original
design because I have added and removed some components. I have also tried
switching to as many SMT components as possible.

The biggest change is the LCD display is mounted on the back of the PCB so
the electronics are all on one board. I have included a mechanical drawing
which should help in making panel cutouts / holes in the front panel of the
case.

The LCD should be mounted on a 0.125” or 3.18mm standoff. To make the
electrical connection, you can use a header like this one:
<https://www.digikey.com/en/products/detail/samtec-inc/TS-116-G-A/1105446>.
Neither of these two parts are listed on the BOM.

Note: the BOM calls for a 4N35. I did not have a library componentfor the 4N27
so I substituted a 4N35 which you can probably use regardless

I cannot take any responsibility for any design issues nor can I
assume any liability for the operation or safety relating to this design.

