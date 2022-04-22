!!! Warning

    This is an experimental project. There is a risk of hurting yourself and/or damaging property when trying to implement or replicate the hardware and/or software. Doing so is completely at your own risk. Take note of our safety guidelines, but don't consider them comprehensive or complete.

This page shows you how the `Gen 3.1` print head prototype was assembled. This is what the finished print head looks like:

![front view of assembled print head](images/print-head-gen3.1/17-assembled-front.jpg)

To build a strong print head, multiple layers made from PCBs are used.
These layers are stacked in the order as they are laid out below:

![all pcb parts](images/print-head-gen3.1/01-pcb-overview.jpg)

First, the inlet and outlet are prepared. To connect Viton tubing to the print head, small copper pipes (`3 mm` diameter) are soldered to the PCB.
The picture shows a larger copper pipe, because the wrong size was used when taking pictures:

![pcb with inlet, outlet and copper pipes](images/print-head-gen3.1/02-inlet-outlet-prep.jpg)

Solder was applied to the pads first:

![inlet pad with some solder](images/print-head-gen3.1/03-inlet-outlet-pre-solder.jpg)

Initially, the solder doesn't want to connect neatly all around the copper pipe. The picture below shows the result of that. Some extra solder was used and placed on such locations. Flux would've probably helped too.

![copper pipe with bad solder connection](images/print-head-gen3.1/05-inlet-outlet-solder-bad-connection.jpg)

Smudges are another problem that might occur while soldering.
It cleaned it off by wiping the (cleaned) soldering iron on it.
It's not problematic if there is some solder on the side,
but I have to make sure it's not sharp.
That way, it won't cut the Viton tubing later on:

![solder smudged on copper pipe](images/print-head-gen3.1/06-inlet-outlet-solder-smudges.jpg)

Finally, there is a neat collar on the copper pipe:

![copper pipe on pcb with solder](images/print-head-gen3.1/04-inlet-outlet-solder-good.jpg)

![finished inlet and oultet on pcb](images/print-head-gen3.1/08-inlet-outlet-solder-finished.jpg)

The next step is to put the monofilament on one of the PCB layers. This monofilament
is what heats up the fuel, which causes the fuel to eject through the nozzle.
The filament gets sandwiched between the nozzle PCB and the PCB that holds the connector.
The filament can be stored in a folded sheet of paper:

![monofilament displayed](images/print-head-gen3.1/09-filament-prep.jpg)

The filament is cut to size. It's good to make it as wide as possible, so it's easier to control and so that we can tape it down on the sides.

![monofilament cut](images/print-head-gen3.1/10-filament-cut.jpg)

Combining the PCBs is tricky, because the filament won't lay still on a flat surface.
In the picture, glue is used to keep the filament in place. In the future, a piece of tape (e.g. Kapton tape) will be a better alternative.

![monofilament glued to PCB](images/print-head-gen3.1/11-filament-glued.jpg)

The nozzle PCB layer had holes that were too small in diameter. They were widened them
by hand with some cheap drills, slowly increasing the diameter `0.1 mm` at a time:

![nozzle PCB with drill in it](images/print-head-gen3.1/12-nozzle-prep.jpg)

A single row of screws combine the two PCB layers. They are not tightened yet:

![nozzle PCB on connector PCB with a single row of screws](images/print-head-gen3.1/13-nozzle-initial-screws.jpg)

Tightening is done carefully and as evenly as possible. When everything stops sliding
around, resistance measurements are done before continueing to tighten further.
The resistance measurements are repeated until the values are in an acceptable range.

![nozzle PCB on connector PCB with all screws](images/print-head-gen3.1/14-nozzle-all-screws.jpg)

The nozzle plate should be placed straigth, unlike in the picture below. In the future, a 3D printable guide will be developed to combine the 2 PCBs with proper alignment.

![nozzle PCB badly aligned with connector PCB](images/print-head-gen3.1/15-nozzle-bad-alignment.jpg)

The prepared PCBs are ready to be combined. I took 8 pieces of `M2 x 10mm` and
some `M2` nuts to match. Medium-strength loctite was also used:

![all layers finished, displayed with M2 hardware and loctite](images/print-head-gen3.1/16-all-layers-ready.jpg)

At this point, I have a finished physical assembly:

![front view of assembled print head](images/print-head-gen3.1/17-assembled-front.jpg)

![back view of assembled print head](images/print-head-gen3.1/18-assembled-back.jpg)

![side view of assembled print head](images/print-head-gen3.1/19-assembled-side.jpg)
