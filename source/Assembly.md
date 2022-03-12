# Getting Started
This section is a visual guide to assembling a 48 DPI (~500 micron dot size) 8 nozzle pyrojetprint head, using nothing but off the shelf parts and basic hand tools. 
The specifications of the finished print head are thus: 
-8 channels, 4 anodes, 4 cathodes
-heater room temperature resistances between 10-100 Ohms, generally clustering around 20-50 ohms
-NTC 5.2E-4 Ohm / K as per https://www.researchgate.net/publication/251168620_Behavior_of_electrical_resistance_of_SiC_CVD_fiber_and_development_of_micro-heater_with_SiC_CVD_fiber?enrichId=rgreq-339d0e561a56379e31178edb041e4233-XXX&enrichSource=Y292ZXJQYWdlOzI1MTE2ODYyMDtBUzoyOTYzNjE0NzcwNjY3NTNAMTQ0NzY2OTQ5MDE4OQ%3D%3D&el=1_x_3&_esc=publicationCoverPdf
-maximum pulse energy tolerance of 100 millijoules, maximum drive voltage, 50 Volts, maximum drive current 500 milliamps. Element is intended to ramp from room tempearature to 1900 K in <= 10 milliseconds.
-Heating element material graphite carbon core Silicon carbide CVD monofilament, 0.135 mm diameter.  0.03mm carbon core diameter. Resistivity of 0.05 Ohm*cm, 2E-4 Ohm*m.
-Board and manifold material : FR4 glass epoxy prepreg board with copper-nickel plated through holes. Inlet and electrical lead side 2.54 millimeter pitch with 1.2mm diameter holes, 2.0 mm wide square pad contacts concentric to holes. Nozzle plate, round 0.635mm diameter holes on 1.27mm pitch, secured to 2.54 mm pitch board with self tapping m1.2 black oxide screws.
-Print head must support capactive touch sensing, temperature monitoring of the heating elements, and IV signal monitoring in the nozzles.
-Should be cheap, costing less than 2 USD / board.
-needs to be scalable to large numbers of nozzles over a large area, and to small feature sizes (small nozzle and heater widths) and thus high cycling frequencies.
-Should be designed to minimize heat loss from the heating element, and from the combustion in the nozzles, this prevents flame quenching as we scale down feature size.

## Scope
Before you get started you should knw that this document is only for the most basic of print heads obtainable with off the shelf parts and materials. This is intended as a very siple first step into the pyrojet project, and towards building your own pyrojet printer.
You will require a few basic hand tools, such a a hack saw and precision screw driver. THe materials for the print head can be a bit odd to source, such as FR4 plated through hole perf boards on 1.27mm pitch, and the of course the silicon carbide monofilament that is the heating element. Unfortunately, it is one of the vey few materials, commercially available that can do the job and do it well. 
Other heating element materials, such as grahite, kanthal, nicrhome, platinum, stainless steel, generally do not have high enough resistance to attain the thermal ramp speed required of the heating element, and/or lack the oxidation resistance, hot creep strength and high melting point (>3100 K ) required to survive repeated exposure to stoichiometric hydrocarbon combustion and molten metal particles..
If you do find another material better suited and more widely available (some kind of oxygen resistant graphite? maybe tungsten carbide?) do not hesistate to make it known and use it!

![description goes here](images/assemblystep1.jpg)
