 - KBIC-225 [controller](https://www.ebay.com/itm/KBIC-SOILD-STATE-VARIABLE-SPEED-DC-MOTOR-CONTROL-KBIC-22S-30-DAY-WARRANTY/181192621391)
 - KBIC controller [HP resistor](https://www.amazon.com/gp/product/B007YA2SJ0/ref=ox_sc_act_title_1?smid=AYJQB4BLLY87P&psc=1)
 - [RTV Silicone Sealant](https://www.zoro.com/i/G2802633/)
 - [Heat gun element](https://www.zoro.com/i/G0394895/)
 - [vacuum motor](https://www.zoro.com/i/G0986632/)

## From "Brewin_Bruin's" project:
https://forum.homeroasters.org/forum/viewthread.php?thread_id=5505&pid=65069#post_65069

 - Ametek Lamb two-stage 2-stage blower (97 CFM, 8.3Amp, 120 V, [1000W electrical] model 116392)
 - DC speed controller (KBIC-125, slightly higher current model than used by OGH). The blower never runs much over half speed, the DC controller is super.
 - single 1700 W heat gun element (Master HAS-043K, 120 V)
 - Bake-a-round 
 - Fire Bricks: Need to be about 2.5 inches thick so that two of them mortared together can have a 3.5" hole drilled in the top
 
hot air recycling
Differences:
I sandwiched the heat gun element between two soft firebricks (the type made for kiln construction, not the fireplace variety). It was easy to cut a channel in the brick, and itâ€™s an excellent insulator for electric current and heat. I still used the mica insulation that comes from Master, but itâ€™s not strictly necessary. (picture 1, 1a). The bricks are mortared together as the next pictures show, and the recess for the 3.5â€ SS tube is cut with a hole saw (top of picture 1, picture 3b)
I used an  vacuum blower with a tangential bypass. I like to keep the motor cooled by ambient air, and the tangential bypass makes it easy to make connections to the heater assembly. (picture #2).
No cocktail shaker. I connected the Bake-a-Round RC to the heater assembly using 3.5 in stainless steel tubing (0.065â€ /16 ga wall thickness) with a stainless V-flange to allow very easy disassembly for dumping coffee and cleaning. (picture 3, 3b) The Bake-a-Round is affixed using a flexible layer of high temp silicone sealant (Permatex 81878 Ultra Copper) nearly 1 mm thick. This compensates for the big difference in thermal expansion between the stainless steel and the Pyrex, the glass would crack if it was tightly sealed. The thermocouple positions are visible here, the one in the RC (BT) is about 2â€ above the perf plate, the ET is just below the perf plate. I use the same 19 hole perf plate pattern as OGH. Nothing is machined or welded, the 20 ga. SS perf plate is silver brazed to the SS tube, and even that isnâ€™t really necessary, you could just use the silicone sealant (soldering is a pain, the thermal distortion works against you). The flanges are a tight fit over the SS tube and stay put (I silver brazed the lower one, again, not really needed.)
The heated air recycling is done using 4â€ metal ductwork form the local home supply, I donâ€™t like to heat PVC routinely, especially around food (picture 4). The chaff collection is easy with the wye-connection to return the air to the vacuum intake. The straight arm dead ends, and the chaff collects there (an internal screen keeps most of it from the intake box) above a gate valve from a shop dust collection system; just open that when done and the chaff dumps out. The air return uses a standard shop vac filter element to prevent chaff from being pulled back into the heater (pictures 4a-4c). I plan to insulate the duct with some old quilt or bath towel at some point. The whole recirculation duct just lifts right off, which I do when Iâ€™m cooling the beans (picture 5). The box is just 3/8â€ scrap plywood, thereâ€™s an opening on the side not visible in picture 4 for the motor cooling flow. Noise is quite tolerable, the firebrick insulation means the wood doesnâ€™t get heated notably.
The system is working nicely with 350 g loads at about 1500 W on the heater (measured with clamp-on ammeter), hitting FC around 9-10 minutes. I have separate cords on the heater and blower, but the combined current is less than 20 A at 120 V, so I could run them off the same circuit (I donâ€™t).
Iâ€™m beginning to grasp how to control my profile better. My setup doesnâ€™t recycle heat as efficiently as OGHâ€™s, but it suits my needs, I prefer somewhat smaller batches. Insulation on the hot air return may lower the heater power somewhat. I will add in an Arduino with three thermocouple mini-boards (Adafruit MAX 31855, the third one is to monitor recycled air) with an LCD screen and a datalogging board when I next have the time to build, replacing my current thermocouple readout. Eventually I may let the Arduino try to control the fan speed, but Iâ€™m not in a rush there, I am my own PID for now.
Final cost US $500-600, including tax & shipping.
