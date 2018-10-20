# Notable OpenSource Projects

Complete, self-hosted home automation systems with frontend, suitable for
end users. At least a year in active development, at least 200 commits,
at least 200 stars.

* [Home Assistant](https://github.com/home-assistant/home-assistant) Site: https://home-assistant.io/, Stars: 16075, Language: Python
* [openHAB](https://github.com/openhab) Site: http://www.openhab.org/, Stars: 3488, Language: Java
* [Domoticz](https://github.com/domoticz/domoticz) Site: http://www.domoticz.com/, Stars: 1520, Language: C++
* [Gladys](https://github.com/GladysProject/Gladys) Site: https://gladysproject.com/, Stars: 876, Language: JavaScript
* [pimatic](https://github.com/pimatic/pimatic) Site: https://pimatic.org/, Stars: 527, Language: JavaScript
* [MajorDoMo](https://github.com/sergejey/majordomo) Site: http://majordomohome.com/, Stars: 288, Language: PHP
* [Freedomotic](https://github.com/freedomotic/freedomotic) Site: http://freedomotic.com/, Stars: 258, Language: Java
* [HomeGenie](https://github.com/genielabs/HomeGenie/) Site: http://homegenie.it/, Stars: 252, Language: C#
* [pilight](https://github.com/pilight/pilight) Site: https://www.pilight.org/, Stars: 229, Language: C

# Notable Commercial Systems

## Revolv

Was a $300 hub, offering a "lifetime subscription".

Acquired by Nest (Google subsidiary) in October 2014. In April 2016, Nest
announced that Revolv Hub will cease to operate on May 15, 2016.
https://en.wikipedia.org/wiki/Nest_Labs#Intentional_disabling_of_hardware_devices


## SmartThings

* 2012-08-23 [KickStarter campaign](https://www.kickstarter.com/projects/smartthings/smartthings-make-your-world-smarter)
  $1.2M/$250K
* 2014-08-14 [Acquired by Samsung](http://www.samsung.com/us/news/23607)
  refs: [(1)](http://linuxgizmos.com/samsung-smartthings-pickup-could-mean-new-role-for-tizen/)
* 2015-01-05 [Hub 2 runs Linux](http://blog.smartthings.com/news/smartthings-updates/new-hub-sensors-optional-services-integrations/)
  refs: [(1)](http://linuxgizmos.com/gen-2-smartthings-hub-migrates-to-linux/)

Uses Groovy language for (custom) components.

* [SmartThings open-source components](https://github.com/SmartThingsCommunity/SmartThingsPublic) Site: http://docs.smartthings.com, Forks: 27667, Language: Groovy


## Vera

Since at least 2008.

Uses Lua, open development support, community ecosystem.


## Wink

* Founded in 2014 as a spin-off from invention incubator Quirky.
* After Quirky went through bankruptcy proceedings, it sold Wink to Flex in 2015.
* In July 2017, Flex sold Wink to i.am+ for $38.7M.


# Related/useful Services and Software

## Dashboards

One of the basic tasks of Home Automation is visualization and control.
Dashboards is a basic way to do that. Dashboard is usually included into
"full stack" HA systems, but what if you don't like it or need a custom
one? Note that majority of systems below offer visualization only (no
control).

* https://github.com/Shopify/dashing - Ruby, 11021 stars, no longer maintained
* https://github.com/evolvedlight/pydashie - "Port of Dashing to Python" 403 stars
* https://github.com/allegro/tipboard - Python, 638 stars
* https://github.com/Freeboard/freeboard - JavaScript, 4766 stars
* Grid Layouts
  * https://github.com/ducksboard/gridster.js - The "default" solution, jQuery plugin (6188 stars)
  * https://github.com/haltu/muuri - No jQuery dep, no item resize (1211 stars)
  * https://github.com/hootsuite/grid (3291 stars)

## Floor Plans

A step above and beyond dashboards is vusualizing what happens where on the
actual floorplan of your home.

* [Sweet Home 3D](https://sourceforge.net/projects/sweethome3d/) - Open Source
  desktop application (Java)
* https://planner5d.com - Online editor, allows to save/import plan in JSON
  format. Image renders are freemium.


---
*Compiled, maintained, content (c) 2017-2018 Paul Sokolovsky*
