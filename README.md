# decent-espresso-tray

This project contains files to print a waste tray and related parts to be used with [Decent Espresso's DE1](https://decentespresso.com) machine together with [Decent's bluetooth scale](https://decentespresso.com/decentscale).

## Motivation
The motivation for this project was [explained here](https://3.basecamp.com/3671212/buckets/7351439/messages/5296473889) but I'll copy/paste the relevant bits below.

> Headline: I've replaced the Decent drip tray with a 3D printed tray that sits above the Decent Scale (DS). This stackup has been working well for me -- from pulling shots by weight, to steaming milk, refilling water,  flushing/routine maintenance, etc. (My DE1 is not plumbed.)
> 
> Pros of this setup:
> * Brew by weight
> * Everything stays put nicely and looks neat
> * The scale is not exposed to liquids/steam
> * The static weight of everything above the scale (minus the SS tray cover) is about 130g
> * Slightly more headroom above the tray (useful for doing a pour-overs, say)

To summarize, this stackup allows the Decent Scale to sit beneath, fitted to, the new drip-tray, in a ready-to-brew configuration. The stackup can be easily moved ouf the way to refill the water tank and the tray can be easily removed and refitted to the scale for emptying or cleaning the former.

## How it works

The Decent Scale has a grippy, rubberized coating on its base to sit securely on most countertop surfaces.

In this stackup, the scale cover fits snugly[^1] over the scale and the tray is glued to the scale cover, making the whole stackup stay put on the counter.

[^1]: The scale cover should be printed in TPU95A or similar material that allows the scale cover to stretch around and grip the scale.

The wire guide (aka wire stent) is necessary when connecting the scale to USB power with the supplied cable as any physical contact interference between the cable and the scale's cover will produce erroneous readings. The wire guide moves the wire away from the scale to avoid interference.

The waste chute extends the waste discharge exit point to the front of the enclosure and thus over the drip tray, allowing the drip tray to capture all the discharge.

## How to print and assemble

### The Drip Tray
Use any non-porous material that is stable up to 150C. In my experience high temperature PLA works just fine. Nylon and polycarbonate would be equally suitable. The material need not be rigid but should not be overly flexible. Do not use CPE as it is porous. *Leak test your tray before proceeding.*

### The Scale Cover 
The STL is sized for TPU95A[^1] to provide a glove-like fit to the scale, yet not so snug that it remains easy to remove and re-install which is a frequent occurrence. TPU95A is a stretchy, rubber-like material. Glue the scale cover and drip tray together with a small amount of cyanoacrylate adhesive such as Krazy Glue.

### The Waste Chute Extender
Print this in nylon, CPE or similar flexible material. Depending on the print method, a little bit of trimming may be needed to clean up supports and left-over build plate adhesion material. *Ensure that the chute completely clear of any leftover print material.* Orient the waste chute extender so that the slot points down and sits over the drip tray. Carefully insert *just enough* of it into the waste chute port on the DE1 until the front edge of the waste chute extender reaches the lower edge of the mirror on the face of the DE1. Test that you haven't inserted it too far by running a shot or screen purge. The volume of the waste water purged should not be affected by the waste chute extender.

### Wire Guide
The wire guide is only necessary if using with USB power (highly recommended), and its only purpose is to guide the USB cable away from the scale so it does not interfere with the scale to prevent erroneous measurements. Firmly press-fit the wire guide with the flared end sitting over the right-angle USB connector's strain relief. Check that you don't have interference issues by wiggling the cable and watching the readout.


--- 
**A Parseeker**, September 2022
