# Design4Us Lab Development Plan

## EYEO Basic Wired 

*Basic wired AT switch interface* 

An interface box that has two 3.5mm jack sockets to allow assistive technology switches to be connected as inputs for assistive technology switches. 

### Why? 

Allows assistive technology switches to control other devices such as mobile devices by acting as if it was a keyboard and sending keystrokes. These can be interpreted computers or other digital devices and use their switch accessibility features. 

### Key Features 

1. Two 3.5mm jack stereo sockets 
2. Enable two channels (switches) per socket using splitter cable 
3. USB C charging. 

### Similar or Competing Products 

Inclusive Switch Interface https://www.inclusive.com/uk/inclusive-simple-switch-box.html 

### Other Notes 

This could also be powered by using a small power bank (such as https://www.amazon.co.uk/Anker-PowerCore-Ultra-Compact-Fast-Charging-Technology/dp/B01CU1EC6Y/) to give wireless functionality if Bluetooth development board used. 

Outputs require an optocoupler – see https://www.instructables.com/Isolating-circuits-from-your-arduino-with-optocoup/ or similar.

Morse will require minimum 3 switches (4 if mode/function change is required).
 
## EYEO Basic Wireless 

*Adaptable wireless AT switch interface*

An interface box that has two 3.5mm jack sockets to allow assistive technology switches to be connected as inputs or for the sockets to act as outputs to emulate assistive technology switches. 

### Why? 

Allows assistive technology switches to control other devices such as mobile devices by acting as it was a wireless keyboard or mouse and sending keystrokes or mouse movements. These can be interpreted by computers or others digital devices and use their switch accessibility features.  

### Key Features 

1. Two 3.5mm jack sockets 
2. Enables two channels (switches) per sockets using splitter cable 
3. Adaptable program to change functionality, such as latched switching 
4. Bluetooth connection 
5. USB C charging 
6. 110mA LIPO battery

### Similar or Competing Products 

* Tapio - https://www.orin.com/access/tapio/ 
* APPlicator - https://www.pretorianuk.com/applicator 

### Other Notes

Also consider ability to solder on cables for serial connections or use JST or similar connector.

## EYEO Switch 

*Wired on/off AT switch*

A wired mechanical AT switch design that can be manufactured using both low volume and higher volume manufacturing techniques.

### Why?

The ultimate design combining simplicity, adaptability and modularity (same design for different sizes) has not been achieved. Commercial switches are great quality but can be expensive. Locally manufactured (3D printed) designs can seem to be lower cost but can be problematic to assemble.

### Key Features

1. use commercially available micro switch(es)
2. design readily adaptable for different switches
3. good consideration for cable management, for example shortening the cable with an easy splice mechanism or cable containment
4. circular
5. 3.5mm jack

### Similar or Competing Products

* Too many to list, for example: https://www.inclusive.com/uk/hardware/switches/button-switches.html

### Other Notes

AT switches can be expensive and there are a number of key features that need to be considered:

* force required for activation
* activation angle or direction of movement
* audible feedback from activation 
* haptic feedback from activation (how it feels)
* size
* material texture
* cable management

## EYEO Switch+

*Wireless and modular AT switch*

### Why?

With switch-based accessibility devices, cable management can become an issue to keep the system tidy. Troubleshooting then becomes difficult as done plugging components in on a daily basis. Existing systems are expensive costing around £200+

### Key Features

1. use commercially available micro switch(es)
2. design readily adaptable for different switches
3. circular
4. 3.5mm jack
5. Bluetooth connectivity
6. Daisy chain wired EYEO Switch

### Similar of Competing Products

* iSwitch https://www.pretorianuk.com/iswitch
* Blue2 FT https://www.ablenetinc.com/blue2-ft/

The typical approach is the use a wireless adapter with standard AT switches.

## EYEO Mob In

*Mobility device input interface box*

### Why?

Novel interfaces or access methods not currently developed for mobility products could be used to drive powered mobility devices.

For someone who is able to accurately guide their finger on a touchscreen mobile device such as a mobile phone. If the finger position was detected on the screen this could then be used to drive the wheelchair proportionally - driven by how far away from an original start point they are.

### Key Features

1. Connect with DB9 9 pin connector on powerchair control system interface box to give proportional or switched control
2. accept switch inputs
3. use on-board or externally sensors to drive powerchair functions
4. connect other external devices such as touch screen or keyboard/mouse to send HID commands
5. consider connecting mainstream products with option of dead-man switch to reduce risk

### Similar or Competing Products

A number of powerchair control systems incorporate an intermediate device between the input device (the switches, joystick or head control for example) and the powerchair input module. Examples are:

* Munevo https://munevo.com/en
* Ability Drive https://www.tolt.tech/products
* Dual Pro https://www.sunrisemedical.co.uk/powered-wheelchairs/switch-it/head-controls/dual-pro
* Vigo https://www.sunrisemedical.co.uk/powered-wheelchairs/switch-it/head-controls/gyroset-vigo

### Other Information:

Have a look at how RelayKeys deals with this https://docs.acecentre.org.uk/products/relaykeys

https://www.dynamiccontrols.com/our-products/linx/auxiliary-modules
https://www.cw-industrial.com/en-gb/medical-mobility/rnet/input-output-module

## EYEO Mob Out

*Mobility device output interface box*

The system used to drive and control a powerchair should be an efficient input method for the user. There is a good chance this input method could be efficient for other systems too such as environmental control, smart homes or other external devices. To void changing between separate input system for each of these devices, an interface box could act as a bridge between the devices.

### Key Features

1. connect with DB9 pin connector on powerchair control system interface box to give proportional or switched control
2. connect with a range of devices
3. consider remote app for control and configuration

### Similar or Competing Products

Powerchair output devices are very rarely used although there may well be benefits.

https://www.dynamiccontrols.com/our-products/linx/auxiliary-modules
https://www.cw-industrial.com/en-gb/medical-mobility/rnet/input-output-module

## D4U Amp

*Adapted mainstream Bluetooth device amplifier*

Mainstream devices used as assistive technology devices for voice output often do not have sufficient volume to manage day-to-day conversations. 

### Key Features

1. use low cost, mainstream Bluetooth speaker
2. 3.5mm AUX input to remove delay if any
3. stereo with at least 2.5A per channel
4. USB-C rechargeable connector preferred
5. attached to case or digital device

### Similar or Competing Products

There are a range of amplifiers that can be used with Bluetooth AT products but none designed specifically for this use case. There are assistive technology devices that incorporate amplification.

### Other Information

There is often a delay waking a Bluetooth device up from sleep mode and this can result in the first part of a spoken sentence being missed. This needs to be checked.

## EYEO Speech

*Mainstream digital device AT enhancement*

Adding additional features to a standard mainstream digital device enables them to be used in an AT environment. It allows costs to be significantly reduced compared to dedicated AT devices which often have high investment costs for manufacture for a relatively low volume. Using mainstream devices benefits from cost reductions that economies of scale can bring if the cost of adding additional features uses low investment manufacturing techniques.

### Key Features

1. handle
2. adjustable orientation
3. ruggedised surround or case, possibly using mainstream case
4. strap for over shoulder carrying
5. ability to add optional keyguards
6. able to attach mounting plate
7. digital device agnostic
8. amplified sound output
9. switch access
10. single point chargin using USB-C
11. integrated mounting system plate

### Similar or Competing Products

* Tobii Dynavox SpeechCase https://uk.tobiidynavox.com/products/speech-case 
* Rehadapt Rehadapter https://rehadapt.com/product/rehadapter-int/ 
* TalkPad https://thinksmartbox.com/talk-pad/ 
* Versa Kit https://www.liberator.co.uk/versaspeaker 

### Other Notes

Nobody has nailed it for desktop manufacture. May want to consider splitting this into two phases:

* Phase 1
  * Items 1-7 above
* Phase 2
  * Items 8-11 above with switch access potentiall provided by a EYEO Switch or EYEO Switch+ board

## EYEO Max

*Modular AT input/output interface box.*

This is the X80 device initially developed with Ace Centre. It is an interface box that can reprogrammed to change the functionality - kind of one box suits many applications. This makes reuse and second life easier and means assessors do not require as much kit.

### Key Features

1. USB charging
2. Wireless
3. Swappable inputs and outputs to allow upto 10 inputs/outputs or some combination
4. One switch "pass through" (one switch input will still control switch output without power
5. Buzzer
6. Setting potentiometer
7. solder pads for connecting wiring direct to board 
8. JST header for input and output
9. Multi function/colour LED (e.g. NeoPixel)

### Similar or Competing Products

* Google Mimosa https://github.com/google/mimosa
* Asterics FABI https://github.com/asterics/FABI

### Other Notes

Need to give consideration to https://github.com/AceCentre/X80

## EYEO Audio Split

*Makes split stereo audio multi-functional*

Splitting the audio on two channels may be useful for some assistive technology users by giving the channels different function. The left channel could be used for audible feedback to user in a headpiece and the the other channel providing speech output to a communication partner.

This is a small PCB with one Jack Input and two Jack outputs.

### Key Features

1. Stereo jack input from digital device audio output (which could be a BLuetooth Receiver Adapter like https://www.amazon.co.uk/Anker-Soundsync-Bluetooth-Connection-Headphones/dp/B07H5C2BQX or https://www.amazon.co.uk/APEKX-Bluetooth-Headphones-Wireless-Hands-Free/dp/B01MUXYVOA)
2. Two mono jack outputs - HEAD1 and HEAD2
3. When there is a jack plug connected in HEAD1 (i.e. headphone plugged in), one channel connects to this and one channel to the speaker
4. When there is a jack plug connected in HEAD2, both channels will be output to the headphones
5. When there nothing is connected to either HEAD1 or HEAD2, both channels output to speakers
6. Two speakers, similar to those used in EYEO Speech

### Similar or Competing Products

None.

### Other Notes

It may be possible to complete this product using cables alone but requires additional investigation. It will only benefit systems where distint functional audio is different on different channels, such as that produced by Pasco (https://github.com/AceCentre/pasco) and Echo (https://github.com/acecentre/echo).

This cable may be useful https://www.kenable.co.uk/en/audio-/audio-cables/jack-extensionssplitters/6058-35mm-stereo-jack-plug-to-twin-35mm-mono-sockets-audio-cable-15cm-006058-5055383460588.html

## MOUNT Mini

*Small AT device mounting system*

Allows small assistive technology devices such as switches to be mounted, positioned and adjusted.

### Key Features

1. Use tool to manipulate and shape mounting tube to reduce joints
2. Use standard tube
3. Able to fix a range of assistive technology switches
4. Compatible diameter with other manufacturer mounting systems
5. Base fixing that enable ease of removal and consistent repositioning
6. Consider swing-away option

### Similar or Competing Products

* Rehadapt https://rehadapt.com/control-mounting/headrest-bundles/
* Mo-vis https://www.mo-vis.com/products/mounting-systems

### Other Notes

The idea is to form standard alluminium tube either 8mm or 10mm diameter using a mini tube bender to get an approximate shape and then tweak by hand. It would be suitable for users who exert a low force that would not reshape the tube. Examples of tube benders include https://www.screwfix.com/p/rothenberger-lever-pipe-bender-6-8-10mm/79571. They are often used in plumbing to form micro-bore tubing.

## MOUNT Adjust

*User positionable lockable mounting arm*

Allows the user to unlock, move and lock a digital device such as an iPad or communication device between different position. This could be to adjust to a more comfortable height, swing to the side to allow for other activies or to change position to take a photograph.

There are many floating arm devices (that can be height adjustable to stay in position once adjusted) on the market for devices such as desktop monitors but they cannot be locked in position. This means they are unsuitable for use on a wheelchair as they would move while the wheelchair is in motion.

### Key Features

1. Unlockable and lockable using a gross movement with one limb
2. Supports its own weight once unlocked and can be height adjusted
3. Once locked, the device cannot be rotated, raised or lowered
4. Standard vese connection
5. 30cm height adjustment

### Similar or Competing Products

* Ideas for Independent Living https://ideasfil.com/lift-and-lock.html
* Rehadapt https://rehadapt.com/product/tc-oh/

### Other Notes

One solution may be to combine the design of a standard monitor mount (such as https://www.amazon.co.uk/ErGear-Monitor-Screens-Adjustable-Rotation/dp/B0C7KPNP7T) but adding a locking mechanism. The locking mechanism of the Manfrotto Variable Fricton Arm (https://www.manfrotto.com/uk-en/photo-variable-friction-arm-with-bracket-244/) may be a useful starting point as this locks and releases with a single release point.

MOUNT Transport

*AT mounting system for transport*

Current guidance for using mounting systems for communication aids generally recommends they are removed if the user is transported in their wheelchair, for example in a wheelchair accessible vehicle or bus. Existing products are not suitable for use in trnasport - this is specifically excluded by the manufacturers.

### Key Features

1. Crash tested and suitable for use in transport
2. Support devices up to 3kg
3. Accept Daessy or Rehadapt mounting reciever
4. One handed removal
5. Adjustable with mount and device in position

### Similar or Competing Products

* Rehadapt https://rehadapt.com/solutions/wheelchair-mounts/standard/
* Daessy https://www.daessy.com/dms/stand_var.html

MOUNT Receiver

*One handed AT device removal*

Existing device mounting system receivers require two hands to remove and fit the device and it can be difficult to judge. Devices have been know to fall to the ground as it has not been obvious if they are attached or not.

A mechanism attached to the device that allow one handed removal in the direction of motion would be easier to use and less prone to error.

### Key Features

1. One handed removal and fitting of the device to the mount
2. Release mechanism on device with handle rather than mount
3. Recieving pin on mount to accept device
4. Self-guiding when replacing the AT device on the mount
5. Passive licking mechanism 
6. Engagement obvious

### Similar or Competing Products

* Daessy Quick Release Bases https://www.aacmounts.com/mmweb/index.php?route=product/category&path=25_68_77
* Daessy Device Plate https://www.tobiidynavox.com/products/daessy-ideas-mount-plate?variant=44351992955072
* Rehadapt Universal Device Socket (UDS) https://rehadapt.com/product/uds-22-quickshift/
* Rehadapt Device Plate https://rehadapt.com/product/ga-vesa-75x75/

OPEN GoBabyGo! 2.0

*Integrated accessible adapted ride-on car*

GoBabyGo! is an initiative to adapt ride-on electric cars with volunteers to provide a basic mobility system to allow children with disabilities to explore, play and learn through independent mobility.

This involved adapting mainstream kids cars to have more supporting seating and to be controled using one or more accessibility switches.

There are other low-cost devices that could be used to provide more functionality sich as line-following and collition avoidance to give more independence than a single direction. Integration with other technologies such as digital devices for communication or control of the environment would further increase independence and autonomy at a time when their peers would be doing the same.

### Key Features

1. Include the functionality of Makeblock mBot2 for line following, collision avoidance and other control mechanisms
2. Adapt mainstream ride-on care which is steered by varying the speed of two powered wheels (NOT through use of a steering wheel)
3. Position EYEO Speech for communication and digital access

### Relevant Resources

* Makeblock mBot2 https://www.makeblock.com/pages/mbot2-coding-robot
* GoBabyGo! https://sites.udel.edu/gobabygo/
* Cole Galloway TEDMED Talk https://www.youtube.com/watch?v=joYgbUWiZAI
* Ride-on cars https://www.smythstoys.com/uk/en-gb/outdoor/electric-ride-ons/c/SM060313

### Other Notes

There are really inspirational videos from Cole Galloway online. The initiative did not really take off in the UK but there are great opportunities to improve this. There are two powered mobility devices developed specifically for kids by charities and available in the UK:

* Bugzi https://www.merushop.org/bugzi-mayhem-at-qef-community-games/
* Wizzybug https://designability.org.uk/assistive-solutions/wizzybug/

# OPEN GoBabyGo! 2.0 Seating

*Postural support for ride-on cars*

To complement the mobility and integration features of OPEN GoBabyGo! 2.0 ride-on car, more supportive seating options will benefit users. This will be linked to the 3D Form projects.

### Key Features

1. Low cost
2. Local manufacture using readily available materials or desktop manufacturing
3. Based on D4U 3D seating technologies

Basing the seating designs on the D4U 3D seating technologies should give higher profile promotion - one product promotes the other.

The types of things used at the moment include foam wedges and inserts, waste pipe and pipe lagging. This gives some minimal support which may be sufficient for some children.

# 3D Buggy Adapt

*Bespoke mainstream buggy postural support*

Specialist buggies for children with disabilities and postural support needs can be expensive and heavy. The have additional supportive elements for the child and will often be manufactured to be suitable for use in transport with the child sat in the buggy. This adds weight, complexity and development cost. It is still recommended that children should be transferred to a car safety seat when travelling in a vehicle as they are designed for this purpose.

Mainstream push chairs and buggies often lack the supportive elements in the right places and of the right strength. They might not have the rigidity and adjustability required for a child with postural needs.

This package will adapt an existing mainstream travel system to provide the postural requirements.

### Key Features

1. Width adjustable pelvic lateral support
2. Seat depth adjustment
3. Height and width adjustable thoracic laterals
4. Head support
5. Pelvic strap
6. Chest harness
7. Adjustable height footrest
8. Allow for growth

It will use a travel system that has:

1. Tilt
2. Folds
3. Optional rain/sun cover

This might include postural support options to improve symmetry and loadbearing for a child in a pram in supine.

Will also need to consider the difference between a Travel System and Stoller.

### Resources

https://www.tendercareltd.com/snappiseat/snappipushchair.html
https://www.rms-rehab.co.uk/marley
https://icklebubba.com/collections/travel-systems

# 3D Form Shell Back

*Digital manufactured custom contoured backrest*

Using an additive rather than a subtractive manufacturing process that scales easily will help to reduce lead times and manufacturing costs. 

Custom contoured wheelchair seating is typically manufacturing by machining a large foam block on a CNC machine to the required size. To enable finishing, this needs to be oversize which leads to a high material and processing cost. 

This product will include a structural shell. Shells are often used in active wheelchair backrests to provide the structural integrity for the foam covering. This system will module and adjustable to reduce stockholding and options. This will allow re-sue with a replacement cushion.

Due to the design of this type of system, it can be difficult for users to dissipate heat and moisture. They do not allow for growth.

### Key Features

1. Scan bean bag cast
2. Translate to surface required in CAD
3. 3D print individual components to provide contour under cushion
4. Attach elements in one orientation
5. Position standard backrest foam with options
6. Built-in height adjustability 50mm
7. Built-in width adjustability 50mm
8. Depth adjustable with replacement lateral wings
9. Ability to add headrest from other manufacturers

The shell will use an existing mounting system uinitially  reduce evelopment time such as V-trak

https://www.v-trak.co.uk/product-category/seating/hardware/v-trak-original/

Cushion arrangement similar to that used in Jay or Matrx backrest.

## Resources 
https://www.youtube.com/watch?v=-81fIa2BPR4
https://www.ottobock.com/en-gb/wheelchairs/custom-seating/shape-carved-foam-seating

Could use Stabilo seating
https://stabilo.krakow.pl/en/stabilo-system-english/
https://mclean-rehatechnik.de/vacuum-bags.html

https://www.sunrisemedical.co.uk/seating/jay/wheelchair-backs/jay-j3-back-sc-mt

https://www.invacare.co.uk/pressure-care-seating/matrx-backs/invacare-matrx-elite-e2-back-series-new

While it is possible to add postural elements to provide additional contouring to these backs, you need specific expertise to position these correctly.

### Related Projects
Form seat
Backrest

# 3D Form Seat

*Digital manufactured custom contour seat*

Uses the skills and knowledge developed with the wheelchair backrest and how this can be translated to seating.

We will also consider whether pressure imaging output correlates to a moulded surface required for optimal positioning and pressure relief.

This may also include standard components that can be added under a standard flat cushion such as a ramp or pre-ishial bar.

The benefit from his approach is it can eb tailored to the user, keeping size and weight down.

This is unique.

### Key Features

1. Elements for custom-contoured seat profile based on user scan
2. Using standard 2D cut standard flat form (so not profiled)
3. Standard range of supportive components for positioning under cushion
4. Rigid base
5. Ramp
6. Pre-iscial bar
7. Pommel
8. Leg gutter/trough
9. Consider built-in lap strap mount (base would require rigid attachment to base)

https://www.xsensor.com/solutions-and-platform/csm/wheelchair-seating

# LIFE2 Powerchair

*Powered mobility product second life*

Powered wheelchairs consist of a number of high value components that consume significant energy during their manufacture. While periphery parts may wear and brake during life, key components often still have a functional life once the product as a whole is written-off for disposal. These include motors, control system and other electrical components. Some items may have been replaced during the life of the product and may also still be usable depending on their last replacement, such as batteries.

There are a range of seating and backrest options on the market, including those forming part of this plan, that could be used to provide the postural element to the wheelchair.

Develop a powerchair chassis with adapter plates that can accommodate a range of used powerchair components from common models.

### Key Features

1. Use motors, control system, castors, wheels from donated wheelchairs
2. Source standard components - armpads, footplates
3. Additional material scrap and recycling, such as metals, will reduce overall cost

Other charities exist, such as Motivation, to encourage local manufacture rather than importing product which is difficult to support and maintain.

https://motivation.org.uk/
https://www.disabilityinnovation.com/

# D4U Powerchair

*Functional feature rich powered mobility*

Powered wheelchair control system have seen little innovation. Whilst specialist control system are available, features such as collision avoidance, seeing behind you, line following, simple driving controls for people with low cognition that provide independence are all system that have been developed but are often expensive to design and implement.

Low cost Arduino-based robots offer much of this functionality at minimal costs. 

1. Single switch (push and go) independent mobility
2. Collison avoidance
3. Line following
4. Obstacle following (wall for example)
5. Mobile device as control interface

### Resources

https://www.makeblock.com/products/buy-mbot2
https://luci.com/
https://www.smilesmart-tech.com/product/smilesmartsystem-powerchairs/

OPEN Access Move System

*Assistive technology quick release implementation*

The Manfrotto MOVE is a lockable mounting system that has an application is assistive technology for quick swap out of access devices such as joysticks or specialist switches during assessment or small digital products such as mobile phones mounted onto wheelchairs.

1. Adapter plate for a range of accessibility switches
2. Adapter plate for a range of accessibility joystick
3. Consider adapter for mobile device

### Resources

https://www.manfrotto.com/uk-en/move-quick-release-system-mvaqr/

OPEN LocLine Switch Mount

*Modular hose assistive technology mount*

Modular Hose, of which Loc-Line is a well know brand, allows manipulation of the attached devices in all directions and allows positioning. Assistive technology switches can be positioned when they are rigidly attached to the end. 

Modular hose is manufactured from acetal copolymer so adhesives to bond it could be investigated to end fittings are fixed.

1. Adapter system for commonly used assistive technology switches
2. Cable running through centre
3. 1/4" mounting to interface with other mounting systems.

### Resources

https://www.loc-line.com/

D4U Paediatric Configurable S/P Wheelchair

*NHS focussed configurable manual wheelchair*

Self-propelling wheelchair typically provided by NHS wheelchair services for kids who self-propel are often scaled down, folding adult wheelchairs. This means they are heavy and contain strengthening components that are often not required. Some of the features that are required for efficient propulsion may not be available such as small castors, short wheelbase, rigid frame, low rolling resistance tyres and it may be difficult to configure the frame.

# Features

1. Single tube fixed frame design
2. Boltable frame and footrest cross brace to enable reconfiguration
3. Rear wheel position movement
4. Seat to ground height adjustment
5. Standard materials for potential local manufacture
6. Push handles 
7. Configurable seat canvas

OPEN Cable Splicing

*Reliable low voltage splicing process"

It would often be beneficial to pass cable through tubing and framework when mounting assistive technology devices to improve appearance and reduce the risk of them getting caught. A reliable and sound technique would help with this. The type of cable this would be with would be switch cable.

1. Splicing mmethod without special tools
2. Splicing method with special tools
3. Splice to be adequately protected

One option would be to use heat shrink solder sleeves or crimp connectors

### Resources 
https://uk.rs-online.com/web/c/cables-wires/cable-joints-cable-sleeving/solder-sleeves/
https://www.youtube.com/watch?v=lmfiOJjRwRk
https://www.screwfix.com/c/electrical-lighting/cable-connectors/cat7230015

OPEN Gooseneck Mount

*Low cost gooseneck device mount*

Light weight assistive technology access devices can be mounted to gooseneck tubing. This may be smaller diameter than a compatrable size modular hose system.

Metal flexible tubing can be used for a switch mount or small devices

It may also be possible to position this inside heat shrink tubing 

### Resources
https://flexible-tubing.com/product-category/stayput-gooseneck-tubing/

OPEN Flexible Mounts

*Low cost flexible device mount*

These generally consist of a spring with tip and heat shrink tubing.

# Features

1. 8mm and 10mm overall size
2. Two spring strength options
3. Threaded end fitting option

















Logos:
LIFE2 - Globe
Open - network/share icon


Other resources to discuss
3D printed cushions


Key Skills to develop
* Remote app for control and configuration and to read/write settings









