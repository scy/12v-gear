# DC Gear

This is supposed to become a curated list of things (mostly electronics, I guess) that work well in a car, campervan, RV, or anything else that can be run from a 12 or 24 volts battery without needing an inverter to generate AC power.

Of course many of these things exist: mobile phones, LED lights, etc.
This list will focus on those items where it’s _unusual_ or _hard_ to find something that runs without AC power.

## Where’s the list?

Currently, we’re collecting raw data and don’t have a nice way to display that data yet.
But you can look at [the raw data](gear.yaml), it’s human-readable.

## What qualifies?

* There are classes of devices which are typically powered by AC or an AC/DC converter (e.g. active USB hubs, screens, hairdryers). Specific models that can also be connected directly to a 12V or 24V battery (e.g. because their AC/DC converter would convert to 12V anyway) qualify, because they might be hard to find, and the output power of their converter is usually not mentioned in product descriptions or even on the box.
* Similarly, if it’s an item of one of these AC categories but it’s powered by USB instead, it qualifies. This is because it’s way easier and more energy efficient to convert 12/24 volts to 5V USB than to 110 or 230 volts AC.
* However, if there are hundreds of models available and they’re really easy to find, these items should not be listed here. Example: 12V microwaves or dishwashers specifically made to be used in vehicles, i.e. normal “RV appliances”.

If in doubt, the rule of thumb is:
Was it really time-consuming and hard to find an item that works AC-less?
Or is it especially cool that this item is DC-powered?
It probably qualifies.

## Can I submit something?

The best way to do that would be to open a pull request, if you know how that works.

The second best way is to create a new [issue](https://github.com/scy/dc-gear/issues).

## Who owns this list?

Currently it’s me, [Tim](https://github.com/scy).
I plan to release the list under some kind of open license, probably CC-BY or something, but I haven’t given it much thought yet.
Right now, the project is more or less my personal list of things, which I happen to display publicly.
