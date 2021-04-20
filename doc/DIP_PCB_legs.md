Following are a few different ways to make DIP legs on PCBs, where the legs are thin enough not to harm sockets of any type, and with little or no shoulder or insulator.

Standard square pin headrs are far too large and completely unsuitable. They physically can't be inserted into machined round sockets, and they damage leaf sockets by over-compressing the contacts.  

Standard machined round pin headers are thinner, but still technically outside what the datasheets of most sockets claim to support, and in many situations there is no room for the large shoulder and insulator.  

# SIL Leadframe
[TE Connectivity 1544210 SIL leadframe](https://www.digikey.com/short/128v4wzj)  

![](sil_legs_1.jpg)

Cut the "busy" ends off the legs with scissors, leaving a simple "comb" of legs.  
![](sil_legs_2.jpg)

Drop that comb down from the top, leaving about 4mm of leg extending from the bottom.  
![](sil_legs_2.jpg)

Solder, then cut the tops off flush.  

# Machined brass micro-pins  
These require no special explaination.

[Mill-Max 3121](https://www.digikey.com/short/vmmq3hf7)

[Keystone 1378](https://www.digikey.com/short/nd73r30q)

# Wire  
[gold-plated brass wire](https://duckduckgo.com/?t=canonical&q=brass+hard+gold-filled+26gauge)

### materials
First you need to find a source for the wire, without getting junk wire that won't work.  
No sellers are writing their item descriptions for electronics, so it takes careful examination to tell suitable products from unsuitable ones.  
There are many small vendors that sometimes have this kind of wire, but they come and go and their stock comes and goes.  

Start with the search above.

You want wire that has the following properties:  
* solid brass  
* 26 gauge / 0.4 mm
* hard or half-hard temper  
* gold filled / gold plated
* round
* no "tarnish resistant" coating

![](wire_legs_wire.jpg)

There are many many products that look the same and have very similar descriptions in their listings.  
You have to look over the descriptions carefully to make sure you don't get gold colored anodized aluminum wire with laquer coating.  
Avoid anything with any of these terms:  
* soft, dead soft
* anti-tarnish, tarnish resistant
* colored

A single foot of wire provides about about 50 legs that are:  
* gold plated  
* the same strength/stiffness as ordinary chip legs  
* malleable enough to survive being bent and straightened a few times  
* small enough diameter not to harm sockets of any type

You also need:  
* a standard breadboard
* a 40 pin single row machined round female pin header
* painters tape

### procedure

Solder the ICs on the PCB before proceeding to the legs.

1. Break the 40-pin socket in half.  
2. Insert the two 20-pin sockets into the breadboard parallel to each other and 0.7 inches apart.  
3. Cover both sockets with painters tape. If you have 3/4" tape, use two pieces of tape, but make sure their is only a single layer of tape covering the actual socket openings on top.  
(These pictures show an 0.6" DIP PCB and an 0.6" DIP socket, but the ram module is 0.7" wide, so you need two separate single-row sockets in place of the DIP socket shown here.)  
![](wire_legs_1-3.jpg)

4. Place the PCB on top of the tape & sockets. Align the PCB with the sockets under the tape.  
5. Hold the roll/loop of wire in one hand with the end of the wire in 2 fingers so that you can poke with it.  
![](wire_legs_4-5.jpg)

6. Poke the wire down from the top of pin #1, through the PCB, punch through the tape, into the socket below, until the wire hits the bottom of the socket.  
   If the wire catches on the edge of the socket:  
   Hold the wire at a point about one inch away from the top of the PCB (meaning maybe back up your grip a little to hold the wire from a little further away from the PCB)  
   Lessen the downward pressure so you're only pushing down lightly  
   Move the wire around/side-side/forward-back a little until the wire drops in.  
![](wire_legs_6.jpg)

7. Cut the wire flush with the top of the PCB.  
![](wire_legs_7.jpg)

8. Repeat 6. and 7. for pin #15 (the opposite corner pin)  
9. Solder those 2 pins.  
![](wire_legs_8-9.jpg)

10 Repeat 6. and 7. for all other pins.  
![](wire_legs_10.jpg)

11 Solder all other pins.  
![](wire_legs_11.jpg)

Done. Lift the module out of the sockets and discard the painters tape.
![](wire_legs_done.jpg)

If you're building multiple modules, use fresh tape for each module.
