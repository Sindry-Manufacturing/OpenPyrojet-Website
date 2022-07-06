# Feedstock

This document contains a list of suggested suppliers and materials for use with the OpenPyrojet print head as well as suggested purchasing, handling and safety information around using the print head and associated fuels and materials.

## The Heating Elements Themselves
[US Suppliers of Silicon Carbide Monofilament](https://www.specmaterials.com/silicon-carbide-fiber-1)  

[Globally Accessible Supplier](https://www.goodfellow.co.kr/en/product/silicon-carbide-monofilament-SI675920.htm)

You can also request a length of monofilament from the US supplier, from Michael (Unit-005) via the discord any time. I keep a few rolls on hand to ensure a continuing supply for various projects.  

## Scope

You should have a basic understanding of what an SDS(Safety Data Sheet) and MSDS(Material Safety Data Sheet) is, and how to read and make sense of them in regards to handling, storing and preparing the various chemicals and materials used in the open pyrojet printhead before reading this document.
Some chemical and materials knowledge(at least undergraduate level) will be helpful here.

Some resources on the above mentioned documents for those who need them, in addition chemical compatibility guides:

- [How to read a Safety Data Sheet / SDS](https://hsi.com/resources/how-to-read-a-safety-data-sheet-sds)
- [How to Read a Material Safety Data Sheet (YouTube)](https://www.youtube.com/watch?v=ZPoFtEBbjWI&ab_channel=BSUBob2008)
- [Chemical compatibility chart on industrialspec.com](https://www.industrialspec.com/resources/chemical-compatibility/)
- [Chemical compatibility chart on case.edu](https://case.edu/ehs/sites/case.edu.ehs/files/2018-02/compatComplex.pdf)

**ALWAYS READ THE SDS AND MSDS and MANUFACTURER HANDLING AND CHEMICAL COMPATABILITY GUIDELINES FOR THE MATERIALS AND FUELS YOU USE IN YOUR PYROJET PRINTHEAD! FAILURE TO DO SO WILL LIKELY RESULT IN DESTRUCTION OF PROPERTY SERIOUS INJURY OR DEATH!**

## Before you begin

The carbides, nitrides and oxides are generally quite benign and inert even as micron powders. I do not recommend eating them, but they are essentially sand paper grit / drill bit / sawblade reinforcements.  So they are quite safe in any quantity.
Pure metals are the biggest real risk to handle and store in general.  of the pure metals, zirconium, aluminum, titanium are probably the most reactive and toxic to human health if we are not discussing alkalis. Like lithium, sodium, potassium. Unless you are planning on printing batteries(which you could) we have no business with alkalis generally, due to their toxicity and explosion hazard.
Titanium, aluminum, and zirconium are all highly flammable even at relatively large particle sizes, oxidize exothermically in air, and can self ignite when simply sitting on a shelf. They are an explosion hazard and potential neurotoxins when aerosolized(which they do readily due to their low specific density among metals). So under no circumstances should you breath or ingest them! Chrome is poisonous if inhaled and a known carcinogen. So stay away from it if at all possible.

Nickel, iron, copper, Zinc, molybdenum, tungsten, and their alloys are generally benign and easy to handle, as long as one does not create dust clouds out of them.

Anything containing silicon is relatively harmless, but can become an airborne silicate if it is very fine, which is essentially like inhaling asbestos. So try to stay away from silicon containing alloys. They have a lot of performance benefits for certain applications. and are really not that dangerous, since they tend to be heavy and difficult to aerosolize. But still. Best not to tango with them if you do not have to.

DO NOT mess with beryllium or beryllia containing compounds unless you have no other choices. They are quite poisonous and can cause berylliosis, which makes mesothelioma look like a joke.

Mercury is probably not available, but if it is, do not mess with it. It and its fumes (easily produced when it boils in a flame) will make you insane and kill you painfully.

Zirconium, titanium and aluminum can be worked with, BUT they require significant care in handling. And splitting kilograms into gram quantities is probably not a safe thing to do without proper dust handling gear, a good respirator(effective for your specific particle size!), gloves, goggles(full face mask if possible) a smock, apron or lab coat rated for flame resistance, with tightly woven pores to resist infiltration and a shop equipped to deal with flammable metal powders(fume extractors, dust filters cyclonic collectors, zero spark low heat motors, anti static work surfaces and tubing etc. Basically everything required for working with gunpowder, solid rocket fuels or other hazardous materials).

In general, unless it is absolutely necessary we prefer to try to derive the more reactive metals from their oxide counterparts, because their oxides are relatively benign, and can be converted to their pure metals via a reducing flame chemistry in the print head. (a fuel rich combustion mixture of air and fuel)

This simple change of approach can eliminate a lot of cost and trouble in dealing with explosive powders.

Basically all super alloys are relatively inert and safe to handle. Inconel, zirconel, stellite, hastealloy, monel, tribaloy, nichrome, kanthal, etc. Are all pretty benign and dense, so they do not aerosolize easily and have few biological effects besides typical metal fever from inhalation(DO NOT breathe it!). Not fun, and not recommended but not particularly deadly or long lasting.

The probable (at the time of writing) lowest cost and lowest risk pure metal feedstocks are Iron, nickel, copper, molybdenum, and tungsten. virtually any oxide or carbide is easy to acquire and safe to handle. Most plastics are safe as well to handle as powders though they still can pose a dust explosion hazard is aerosolized as most powders do. In short DO NOT AEROSOLIZE THE POWDERS OUTSIDE OF THE PRINT HEAD!

They should be pretty affordable(10-100 USD per kilogram), and allow us to do a variety of useful things, like making alloys, strong mechanical parts, and electronics.
Additionally, noble metals, though very expensive, make for great feed stocks. Silver, gold and platinum are the "gold standard" for making dense, pure electrically conductive metal parts and tracks for electronic devices. They are also relatively benign, bioinert and non explosive thanks to their resistance to oxidation. Though their nanoparticle varieties can interact with one's genes in undesirable ways. DONT EAT THESE!

## Fuels

Viable fuels for pyrojet can be just about any combustible substance than can flow through the print head. This includes generally, ethanol, Acetone, IPA, glycerol, gasoline, methanol, Nitromethane, paraffin, PLA, ABS, ASA, naptha, hexane, decane, motor and gear oil, WD-40,Kerosene, virtually any long chain hydrocarbon, combustible alcohol, alkene, alkane, or other fuel.

These fuels are COMBUSTIBLE, and FLAMMABLE, this means that they can EXPLODE and seriously injure or kill the unwary, unwitting or fool hardy who disrespect or misuse them. DO NOT UNDERSTIMATE THE DANGER OF THESE FUELS. It only takes a second for an accident to become a fuel air bomb, or a high explosive. DONT BECOME A STATISTIC BECAUSE YOU DID NOT READ AND FOLLOW APPROPRIATE SAFETY PRECAUTIONS.

**MANY FUELS RELEASE NOXIOUS BYPRODUCTS like acrolein, acetylaldehyde, formaldehyde, nitric acid, CO and CO2, WHEN COMBUSTED AND CONSUME OXYGEN, THIS MAKES THEM A HEALTH HAZARD WHEN BURNED IN A CLOSED SPACE AND CAN SUFFOCATE YOU BY CONSUMING ALL THE OXYGEN IN YOUR WORK SPACE!
ENSURE ADEQUTE VENTILATION AND KEEP A FIRE EXTINGUISHER FIRE BLANKETS AND KAOLITE HANDY. BE SURE TO KNOW YOUR ESCAPE ROUTES AND TAKE STOCK OF POTENTIAL CONSEQEUNCES IF THINGS GO BAD AND GET OUT OF HAND. WHILE WE HAVE TAKEN EVERY EFFORT TO ENSURE THE SAFETY OF THE OPERATOR IN THE DESIGN OF THE PRINTER THE GREATEST BARRIER TO DISASTER IS YOU AND YOUR PREPAREDNESS AND CONTINUAL OBSERVANCE OF ALL NECESSARY PRECAUTION WHEN OPERATING THE PYROJET DEVICE!**

## Further notes

Our preferred feedstock materials are spherical particles between 1 and 50 microns in diameter. smaller and larger sizes will work to a point, but have a variety of complications around their tendency to settle and clog (for big particles) or to aggregate and clog (for very small particles). Our preferred fuel is either, Ethanol, methanol, naptha(white gas/coleman fuel), or common low octane unleaded gasoline. Additionally, the use of solutions of [metal salts](https://en.wikipedia.org/wiki/Salt_(chemistry) such as chlorides or sulphates in these fuels can be used to eliminate the need for metal powders if one is inclined to a more chemical solution and is having trouble with clogging and other issues witch plague pigment approaches. Metal salts allow for deposition of very thin films to very thick films with a great deal of variety in their structure and qualities depending on the specific deposition conditions and solution chemistry. This is still an active area of research.  

The reason we like white gas and ethanol best, is thanks to their high energy density, relatively benign combustion products, and fast, clean burning behavior.  White gas is easier to ignite and burns hotter, and is easy to store and transport. Ethanol is common and very clean burning, though it has about half the energy density of white gas. So it will make for slower prints for most materials. Methanol/ethanol requires less oxygen for complete combuston however, and when mixed with an oxidizer such as nitromethane can approach the volumetric energy density of white gas, while producing much less coking(carbon soot) while being much less reactive with many metals. This aspect of Pyrojet still needs a lot of work and we need a lot of help! :)

## Suppliers

These are known helpful feedstock suppliers:

### USA

- [beantownchem.com](https://beantownchem.com/) (bean town can also provide ethanol, and other liquid fuels stocks)
- [Walmart naphta](https://www.walmart.com/ip/Crown-White-Gas-Camp-Fuel-for-Use-in-Gasoline-Stoves-and-Lanterns-1-Gallon/51741744)
- [HomeDepot naphta](https://www.homedepot.com/p/Klean-Strip-1-qt-Varnish-Maker-and-Painter-s-Naphtha-QVM46/100122813) (same thing as white gas basically)

### Europe

- [fst.nl](https://www.fst.nl/consumables/thermal-spray-powders.html) - feedstock (minimum quantity is 2.5 or 5 kg)

## Safety gear

These are websites where you can buy safety gear, or find information about it:

- [https://multimedia.3m.com/mws/media/639110O/3m-respirator-selection-guide.pdf](https://multimedia.3m.com/mws/media/639110O/3m-respirator-selection-guide.pdf)
- [https://labcoats.mit.edu/guidance](https://labcoats.mit.edu/guidance)
- [https://labcoats.mit.edu/pyrophorics](https://labcoats.mit.edu/pyrophorics)
- [https://www.additivemanufacturing.media/articles/safety-tips-for-metal-am](https://www.additivemanufacturing.media/articles/safety-tips-for-metal-am)
- [https://www.makepartsfast.com/ensure-safe-usage-additive-manufacturing-systems/](https://www.makepartsfast.com/ensure-safe-usage-additive-manufacturing-systems/)
- [https://www.osha.gov/sites/default/files/publications/OSHA3912.pdf](https://www.osha.gov/sites/default/files/publications/OSHA3912.pdf)
- [https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.109](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.109)
- [https://fireprevention.utexas.edu/firesafety/abcs-fire-extinguishers](https://fireprevention.utexas.edu/firesafety/abcs-fire-extinguishers)
- [https://www.homedepot.com/b/Electrical-Fire-Safety-Fire-Extinguishers/N-5yc1vZbmgp](https://www.homedepot.com/b/Electrical-Fire-Safety-Fire-Extinguishers/N-5yc1vZbmgp)
