The time has come… to have some phun.

# CORE

We have promised to keep the initial topic around sustainable urban development. The hackathon.lu team has provided us with some of their sources for you to get cracking with.
Whilst we will never know what the initial plan was, we will make it our plan.

Bare in mind that we are in a Hackerspace with a plethora of geeky goodness.
There are Arduino Microcontrollers, Raspberry Pi machines, more sensors then you could wish for (UV, Sound, Light, GPS etc), 3D Printer, CNC Mill.
So why not go Hardware?

Perhaps you already have an idea on what issue to tackle if you haven't, brainstorm.

Think about that last confusing walk in the park, your last mushrooms form china shopping at the market, your stroll through the woods, your thirsty jog through the city.
The author of this text seems to strongly lean towards sustainable urban ecological development. So what does Wikipedia say arbout Sustainable urbanism:

"Sustainable Urbanism, as a defined term, is application of sustainability and resilient principles to the design, planning, and administration/operation of cities. There are a range of organizations promoting and researching sustainable urbanism practices including governmental agencies, non-governmental organizations, professional associations, and professional enterprises around the world. Related to sustainable urbanism is the Ecocity movement (also known as Ecological Urbanism) which specifically is looking to make cities based on ecological principles, and the Resilient Cities movement addresses depleting resources by creating distributed local resources to replace global supply chain in case of major disruption. Green urbanism is another common term for sustainable urbanism. Sustainable development is a general term for both making both urban and economic growth more sustainable, but isn't specifically a mode of urbanism.

Sustainable urbanism aims to close the loop by eliminating environmental impact of urban development by providing all resources locally. It looks at the full life cycle of the products to make sure that everything is made sustainably, and sustainable urbanism also brings things like electricity and food production into the city. This means that literally everything that the town or city needs is right there making it truly self-sufficient and sustainable."

Happy Hacking on this one.

Sooooo, we want to extend the challenge by providing some data you can get creative with.

# Heat my map

When we think data, we lust for computer readable *stuff*

But the real world teaches us on tough lesson every-time we get eager to distil that funky data source only to realize that it is a PDF or even worse a low quality image file with some data already visualized.

Below we have a heat-map of the noise pollution levels in various areas of Luxembourg.
Very valuable data but no real way to extract anything from it because the sources are, well, somewhere.

Your task could be to come up with the heatmap2text parser.

Do not limit yourselves to the 2 text part. If you think that such an image can make an interesting sound or can be used as the basis of anything else, do it.

http://www.environnement.public.lu/air_bruit/dossiers/BR-bruit/bruit_cartes_et_valeurs_limites/cartes_plan_action_aeroport.pdf

http://www.environnement.public.lu/air_bruit/dossiers/BR-bruit/bruit_cartes_et_valeurs_limites/cartes_plan_action_routes.pdf

# What time (zone) is it?

Geeks are everywhere and we have taken over the world ever since Grace Hopper wrote her first line of, errr… punch cards.
One geek niche is the beautifully confusing realm of TimeZones.

For the *nix folks, more specifically the sudo apt-get update; sudo apt-get dist-upgrade adventurers, there is a recurring theme in how frequent the package *tzdata* gets updated.

From countries who have a 30 minute time zone offset to countries who have frequent brawls about daytime savings time, every single weirdness has been meticulously documented by the TZ geeks.

The following dataset has it all. It is a text file, but that makes it not necessarily very parsable or useful for the rest of us.
This is also the file that gets processed by the various package systems to update the operating systems time zone data.

Take a deep breath and look at what is inside. Does it make music? Is there a hidden message? What do all the current time zones look like in the most esoteric diagram you know?

Play with it. You have all the creative liberties on this one. May it be an interactive tzdata map, or an audio generator.

Time zone data can be art, oh wait, there is even an FTP location with examples :D

ftp://ftp.iana.org/tz/tz-art.html

ftp://ftp.iana.org/tz/

ftp://ftp.iana.org/tz/releases/

https://www.iana.org/time-zones

https://blog.jonudell.net/2009/10/23/a-literary-appreciation-of-the-olsonzoneinfotz-database/
