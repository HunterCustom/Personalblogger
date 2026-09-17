---
title: "Building the Miata’s Fuel System: How a Simple Fuel Pump Upgrade Got Completely Out of Hand"
date: 2025-12-28 12:00:00 -0500
categories: [Miata, Fuel System]
tags: [miata, nb-miata, fuel-system, dw300, id1050x, an6, e85, flex-fuel, radium-engineering, haltech]
description: "What started as a DW200 and 640cc injector upgrade turned into a DW300, ID1050Xs, a return-style -6AN fuel system, flex-fuel sensor, and a growing hatred of working with gasoline."
---

I swear, every time I think I've figured out this Miata build, I discover another thing that needs to be upgraded.

This time, it's the **fuel system**.

What started as a relatively simple fuel pump and injector upgrade has somehow turned into replacing practically the entire fuel system.

New pump. Bigger injectors. Fuel pressure regulator. Pulse damper. Ethanol sensor. Fuel lines. Bulkhead fittings. Electrical pass-throughs...

At this point, I might as well just build the entire damn car from scratch.

But hey, at least I'll have a fuel system that can support my future power goals without having to tear everything apart again.

## The Original Plan: DW200 and 640cc Injectors

When I first started planning the fuel system for my **1999 Mazda Miata**, I figured a **DeatschWerks DW200** fuel pump and **640cc injectors** would be enough.

Then I went back and looked at my fuel calculations again.

Yeah...

**My math was bad.**

For context, the long-term goal for this Miata is approximately **350 wheel horsepower**, and I also want enough headroom to potentially run E85 later.

Rather than build a fuel system that I'd eventually have to upgrade *again*, I decided to step things up.

The revised setup is:

- **DeatschWerks DW300 fuel pump**
- **Injector Dynamics ID1050X injectors**

The ID1050Xs give me considerably more room to work with, especially once ethanol gets involved.

Of course, changing the pump and injectors was only the beginning.

Because apparently I can't leave anything alone.

## The Fuel Pressure Regulator Rabbit Hole

My original plan was to retain as much of the factory Miata fuel system as possible.

I figured I'd use the stock fuel-pressure regulator and factory fuel pulse damper.

Simple.

Cheap.

Easy.

Naturally, that's not what happened.

Somehow I ended up with a **Radium Engineering direct-mount fuel pressure regulator**.

Then I started looking deeper into the pulse damper setup and realized Radium also makes a **direct-mount fuel pulse damper** that should integrate much more cleanly with what I'm building.

So now we're doing that too.

The regulator will handle fuel pressure control, while the pulse damper helps reduce the pressure pulsations created by the injectors opening and closing.

At this point, things were already getting substantially more complicated than:

> "Throw a bigger fuel pump in it."

And then I started thinking about ethanol.

## Adding a Flex-Fuel Sensor Because Apparently I Hate Money

Most pump gasoline around me contains ethanol, but the actual amount isn't necessarily identical every single time you fill up.

Something sold as E10 doesn't mean you're guaranteed to have exactly 10% ethanol in the tank at all times.

That made me start thinking...

If I'm already rebuilding practically the entire fuel system, **why not add an ethanol-content sensor now?**

I'm also planning on moving south, most likely to **North Carolina**, and E85 availability should be considerably better than what I'm currently used to.

So I figured I might as well give the car the hardware necessary for future flex-fuel capability.

The plan is to use a **GM-style flex-fuel sensor** and feed ethanol-content data into the **Haltech Elite 1500**.

> Installing an ethanol-content sensor by itself does **not** make the car flex-fuel capable. The ECU still needs to be properly configured and tuned, and every fuel-system component needs to be compatible with the ethanol concentration being used.
{: .prompt-warning }

But if I'm already building the system...

I would much rather install the sensor now than rebuild another section of the fuel system later.

**Future-proofing!**

Or at least that's what I'm telling myself to justify spending more money.

## Wait... Now I Need a Return-Style Fuel System?

This is where things really started getting out of hand.

The factory NB Miata fuel system regulates fuel pressure back near the tank rather than using the traditional engine-bay regulator and dedicated return line that I want for this setup.

Once I decided to use the Radium regulator, converting the car to a **return-style fuel system** started making a lot more sense.

Which immediately raised one very simple question:

**How the fuck do I actually do that?**

I found a guide on MiataTurbo.net covering a similar conversion.

The information itself was useful, but the guide was pretty janky, difficult to follow, and seemed to assume I already understood half of what it was trying to explain.

I didn't.

So I had ChatGPT reorganize and rewrite the information into something a dumbass like me could actually understand.

That helped tremendously.

Unfortunately, understanding it better also made me realize how much of the fuel system I was about to change.

![Factory NB Miata fuel tank and pump assembly](nb-miata-fuel-tank-diagram.png){: w="1064" h="541" }
_The factory NB Miata fuel tank and pump assembly. This innocent-looking thing is where a large portion of my problems are about to begin._

Once I started looking at the factory hardlines, quick-connect fittings, tank assembly, and all the adapters I'd need...

I made another decision.

## Screw It. We're Going Full -6AN.

Originally I was planning to retain the factory fuel lines and just adapt everything as necessary.

Technically, I could do that.

But the more I looked at it, the less I liked that idea.

I'd end up with factory lines going into adapters, going into AN fittings, going into aftermarket components, and probably another adapter somewhere else.

At that point I'm doing a ton of work while still designing the system around the factory plumbing.

So...

**Yup. We're just swapping the entire fuel system to -6AN.**

Both the feed and return will use **-6AN hose**.

The larger plumbing gives the fuel system plenty of potential flow capacity for my goals, although obviously hose diameter isn't the only thing determining fuel flow. The pump, filter, regulator, fittings, voltage, and other restrictions all matter too.

For me, though, one of the biggest advantages is simply consistency.

Instead of constantly figuring out how to adapt Mazda's original plumbing to whatever part I'm installing, I'll have a common fitting standard throughout the new system.

Would keeping the stock lines have been cheaper?

**Absolutely.**

Would keeping them have been easier?

**Probably.**

Do I want to rebuild the fuel system a second time?

**Absolutely fucking not.**

I hate working with fuel.

I hate the smell.

I hate worrying about leaks.

And I especially hate the idea of finishing all of this just to discover that there's another part of the system I should have upgraded while everything was already apart.

So -6AN it is.

> Please do not burn my Miata down.
{: .prompt-danger }

## Modifying the Fuel Pump Assembly

Once I committed to -6AN lines, the next problem was figuring out how I wanted to modify the fuel pump assembly itself.

I need to get two things through the top of the tank:

1. **Fuel**
2. **A lot more electrical current**

### Upgrading the Fuel Pump Electrical Connections

With the DW300, I don't really want to rely on tiny factory wiring if I can avoid it.

So I decided to install **M6 electrical studs** through the fuel-pump hanger for both positive and negative.

I'm planning to use **Boost Monkey electrical pass-through bulkheads**.

That gives me proper terminals where I can attach substantially larger wiring on both sides of the fuel-pump assembly.

It should make it much easier to give the DW300 a solid electrical supply without forcing higher pump current through the factory connector.

Of course, I'll still need to make sure the:

- Wire gauge is appropriate
- Terminals are properly crimped
- Pass-throughs seal correctly
- Pump is fused correctly
- Relay and wiring are rated for the pump's current draw

Fuel and electricity are two things I'd particularly prefer not to screw up at the same time.

## Choosing the Fuel Bulkhead Fittings

My first thought was to use a standard straight **-6AN bulkhead fitting** through the fuel-pump hanger.

ChatGPT had originally suggested doing exactly that.

But the more I looked at it, the more I wondered:

**Why?**

If I use a straight -6AN bulkhead fitting, I would then need another adapter *inside the fuel tank* to transition from -6AN to the 5/16-inch hose feeding the pump.

That's another fitting.

Another connection.

Another clamp.

Another potential failure point.

I don't really want additional connections inside a fuel tank if I can avoid them.

So I kept looking and found something that makes significantly more sense for my setup:

**-6AN bulkhead fittings with an integrated 5/16-inch hose barb on the inside.**

I'm using **Evil Energy -6AN bulkhead-to-5/16-inch-barb fittings**.

I'll need two:

- One for the **feed**
- One for the **return**

Externally I get my -6AN connection.

Internally I get a direct 5/16-inch hose barb.

No additional AN-to-barb adapter required inside the tank.

**One less failure point.**

I'll take it.

## Replacing the Internal Tank Plumbing

Since I'm modifying the pump hanger anyway, I'm also replacing the relevant internal fuel plumbing.

For the submerged connections, I bought **Evil Energy SAE 30R10 fuel hose**.

SAE 30R10 hose is designed for fuel-system applications where the hose is continuously submerged in fuel, unlike ordinary fuel-injection hose that may only be designed to contain fuel internally.

> Don't substitute ordinary external fuel hose for submerged in-tank hose. Before final assembly I'm also verifying that the exact hose, seals, clamps, bulkheads, and other wetted components I'm using are compatible with the ethanol concentrations I eventually plan to run.
{: .prompt-warning }

The plan is to replace the internal hardline arrangement where necessary and connect the DW300 directly to my new bulkhead fitting using the submersible hose.

That should give me a much simpler path:

**DW300 → 30R10 hose → 5/16" barb → bulkhead → -6AN feed line**

Beautiful.

Well...

As beautiful as something sitting inside a bucket of gasoline can be.

## What About the Fuel Filter?

Naturally, changing all the lines created another problem.

**The fuel filter.**

The OEM Miata filter uses factory quick-connect fittings.

I could absolutely adapt those fittings to -6AN.

But now we're back to the exact thing I'm trying to avoid:

**Adapters on adapters on adapters.**

I also started wondering whether there was any reason to retain the factory filter when practically everything surrounding it is being replaced.

So I'm not.

I bought an **Evil Energy 10-micron inline fuel filter** that can integrate directly into the -6AN system.

I'll still verify the filter's rated fuel flow and ethanol compatibility before final installation.

A filter saying "10 micron" doesn't automatically mean it's appropriate for every EFI fuel system.

I'm also keeping the fuel pump's inlet strainer in mind because the post-pump filter isn't the only filtration in the system.

I'm trying to build a fuel system that actually works correctly...

not just one with a bunch of cool-looking AN fittings.

Although AN fittings **do look pretty damn cool**.

## Protecting the Fuel Lines From Heat

Since the car is eventually going to be turbocharged, fuel-line routing around heat is another thing I don't want to ignore.

The engine bay is going to get substantially hotter once the turbo, manifold, downpipe, and exhaust system are all crammed in there.

I don't want fuel lines casually hanging around next to hot exhaust components.

So I ordered:

**6× DEI Heat Sheath — 1/2-inch × 36-inch**

Total cost:

**$101.94**

That should give me enough material to protect the portions of the -6AN lines that need additional thermal shielding.

I'll figure out exactly where I want the sleeving once the fuel lines are physically routed through the car.

> Heat shielding isn't a replacement for proper fuel-line routing. Wherever possible, I'm still going to maximize clearance between the fuel system and the turbo/exhaust components.
{: .prompt-info }

## Current Fuel System Parts List

Here's where the fuel system currently stands.

| Component | Part |
|---|---|
| Fuel Pump | DeatschWerks DW300 |
| Fuel Injectors | Injector Dynamics ID1050X |
| Fuel Pressure Regulator | Radium Engineering Direct-Mount Fuel Pressure Regulator |
| Fuel Pulse Damper | Radium Engineering Direct-Mount Fuel Pulse Damper |
| Ethanol Sensor | GM Flex-Fuel Sensor |
| ECU | Haltech Elite 1500 |
| Fuel Filter | Evil Energy 10-Micron Inline Filter |
| Fuel Bulkheads | 2× Evil Energy -6AN to 5/16" Barb Bulkheads |
| Electrical Bulkheads | Boost Monkey M6 Electrical Pass-Throughs |
| In-Tank Fuel Hose | Evil Energy SAE 30R10 |
| Feed Line | Evil Energy Anti-Static -6AN Hose |
| Return Line | Evil Energy Anti-Static -6AN Hose |
| Fittings | AN8 ORB to -6AN, AN6 ORB adapters, 90° swivel fittings |
| Heat Protection | 6× DEI 1/2" × 36" Aluminized Heat Sheath |

This is the **current** parts list.

It is definitely not the final parts list.

Because let's be realistic:

There is absolutely no chance I get through this project without realizing I need another fitting.

Or ordering one fitting in the wrong size.

Or ordering the correct size with the wrong thread.

Or discovering that the fitting I need exists but costs $37 for absolutely no reason.

That's just how AN plumbing works.

## The System I'm Trying to Build

At this point, the basic plan looks something like this:

```text
FUEL TANK
   │
   ├── DW300 Fuel Pump
   │
   ├── SAE 30R10 Submersible Hose
   │
   └── -6AN / 5/16" Bulkhead
            │
            ▼
       -6AN Feed Line
            │
            ▼
        Fuel Filter
            │
            ▼
      GM Flex Sensor
            │
            ▼
         Fuel Rail
       ID1050X Injectors
            │
            ▼
   Radium Fuel Pressure
        Regulator
            │
            ▼
       -6AN Return
            │
            ▼
         Fuel Tank
```

The exact placement of the flex-fuel sensor, filter, regulator, and fittings may change once I physically mock everything up.

That's why I'm trying very hard not to cut any hose until I have everything sitting in front of me.

## Why I'm Doing All This

This probably looks like an absurd amount of work for a car that hasn't even reached the 350 WHP goal yet.

And...

Yeah.

It kind of is.

But the way I see it, I have two options.

I can build the minimum fuel system required right now and potentially redo portions of it later.

Or I can build the fuel system once with:

- A DW300
- ID1050X injectors
- -6AN feed
- -6AN return
- Adjustable fuel-pressure regulation
- Fuel pulse damping
- Ethanol-content sensing
- Future E85 compatibility
- Upgraded pump wiring

I'd rather suffer once.

At least that's the theory.

## What's Next?

Everything I've ordered should be here **Thursday**.

Once everything arrives, I can start physically mocking up the system and figuring out whether all of these ideas actually work together in the real world.

The next major jobs will be:

- Pulling the fuel-pump hanger
- Figuring out bulkhead placement
- Drilling the hanger for the new fittings
- Installing the M6 electrical pass-throughs
- Installing the new feed and return bulkheads
- Plumbing the DW300 inside the tank
- Routing the -6AN feed line
- Routing the -6AN return line
- Mounting the fuel filter
- Mounting and plumbing the flex-fuel sensor
- Connecting the Radium regulator
- Wiring the ethanol sensor into the Haltech
- Wiring the DW300 properly
- Pressure-testing everything
- Checking obsessively for leaks

That last one is going to happen approximately 400 times.

> Before actually running the car, the completed fuel system will be checked for leaks, secured away from moving/hot components, and pressure-tested. Fuel-system modifications are one of those jobs where "eh, that's probably fine" isn't good enough.
{: .prompt-danger }

I'll document the installation as I go, including what works, what doesn't, and what parts I inevitably end up ordering twice.

For now, though, the fuel system has officially gone from:

**"Let's install a bigger pump."**

to:

**"We're replacing basically everything."**

What started as a **DW200 and 640cc injectors** has turned into a **DW300, ID1050Xs, -6AN return-style fuel system, upgraded pump wiring, Radium regulator, pulse damper, and future flex-fuel capability**.

All because I decided to double-check my fuel calculations.

I hate working with fuel.

---

## Build Specs

- **Car:** 1999 Mazda Miata NB1
- **Engine:** BP
- **ECU:** Haltech Elite 1500
- **Power Goal:** ~350 WHP
- **Fuel Pump:** DeatschWerks DW300
- **Injectors:** Injector Dynamics ID1050X
- **Fuel Lines:** -6AN feed and return
- **Fuel Pressure Regulation:** Radium Engineering
- **Flex-Fuel Sensor:** GM ethanol-content sensor
- **Future Fuel:** Pump gas / E85 / flex-fuel