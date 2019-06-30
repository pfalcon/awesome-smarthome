# Awesome SmartHome [![Awesome][awesome-badge]][awesome-link]

> :house: A curated list of awesome tools, resources and other shiny thinks for home automation.

Home automation is the integration of the systems in indoor spaces, to centralize the control and grant autonomy.
It uses technologies from electronics, computer science, automation and telecommunication on top of the usual systems for:
- climate
- security
- lighting
- access control
- entertainment

# Notable OpenSource Projects

Complete, self-hosted home automation systems with frontend, suitable for
end users. At least a year in active development, at least 200 commits,
at least 200 stars.

* [Home Assistant](https://github.com/home-assistant/home-assistant) Site: https://home-assistant.io/,
  ![stars](https://img.shields.io/github/stars/home/home.svg?style=social)
  ![Python Language][python-badge]
* [openHAB](https://github.com/openhab) Site: http://www.openhab.org/,
  ![stars](https://img.shields.io/github/stars/openhab/openhab-distro.svg?style=social)
  ![Java Language][java-badge]
* [Domoticz](https://github.com/domoticz/domoticz) Site: http://www.domoticz.com/
  ![stars](https://img.shields.io/github/stars/domoticz/domoticz.svg?style=social)
  ![C++ Language][cplusplus-badge]
* [Gladys](https://github.com/GladysProject/Gladys) Site: https://gladysproject.com/,
  ![stars](https://img.shields.io/github/stars/GladysProject/Gladys.svg?style=social)
  ![JS Language][javascript-badge]
* [pimatic](https://github.com/pimatic/pimatic) Site: https://pimatic.org/,
  ![stars](https://img.shields.io/github/stars/pimatic/pimatic.svg?style=social)
  ![JS Language][javascript-badge]
* [MajorDoMo](https://github.com/sergejey/majordomo) Site: http://majordomohome.com/,
  ![stars](https://img.shields.io/github/stars/sergejey/majordomo.svg?style=social)
  ![PHP Language][php-badge]
* [Freedomotic](https://github.com/freedomotic/freedomotic) Site: http://freedomotic.com/,
  ![stars](https://img.shields.io/github/stars/freedomotic/freedomotic.svg?style=social)
  ![Java Language][java-badge]
* [HomeGenie](https://github.com/genielabs/HomeGenie/) Site: http://homegenie.it/,
  ![stars](https://img.shields.io/github/stars/genielabs/HomeGenie.svg?style=social)
  ![C# Language][csharp-badge]
* [pilight](https://github.com/pilight/pilight) Site: https://www.pilight.org/,
  ![stars](https://img.shields.io/github/stars/pilight/pilight.svg?style=social)
  ![C Language][c-badge]
* [Jeedom](https://github.com/jeedom/core) Site: https://www.jeedom.com/site/en/,
  ![stars](https://img.shields.io/github/stars/jeedom/core.svg?style=social)
  ![PHP Language][php-badge]
* [FHEM](https://github.com/mhop/fhem-mirror) Site: https://fhem.de/, Revisions: 19211
  ![Perl Language][perl-badge]
* [MisterHouse](https://github.com/hollie/misterhouse) Site: http://misterhouse.net/,
  ![stars](https://img.shields.io/github/stars/hollie/misterhouse.svg?style=social)
  ![Perl Language][perl-badge]

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

* [SmartThings open-source components](https://github.com/SmartThingsCommunity/SmartThingsPublic) Site: http://docs.smartthings.com
  ![stars](https://img.shields.io/github/stars/SmartThingsCommunity/SmartThingsPublic.svg?style=social)
  ![Groovy Language][groovy-badge]


## Vera

Since at least 2008.

Uses Lua, open development support, community ecosystem.


## Wink

* Founded in 2014 as a spin-off from invention incubator Quirky.
* After Quirky went through bankruptcy proceedings, it sold Wink to Flex in 2015.
* In July 2017, Flex sold Wink to i.am+ for $38.7M.


# Home Automation Services

## Voice Assistants

Previously, government and mob had to break into your house to install bugs.
Now you can pay a small amount of money and install yourself bugs which allow
3rd parties to eavesdrop on you.

* Apple Siri
* Amazon Alexa
* Google Assistant

OpenSource services promising no eavesdropping (please keep in mind that for
some of these projects, "OpenSource" is just a marketing bait):

* [Mycroft.AI](https://mycroft.ai/), code: https://github.com/MycroftAI
* [Snips](https://www.snips.ai/), code: https://github.com/snipsco/
  * Some links point to https://github.com/snipsco/snips-platform , which isn't available.
    https://github.com/snipsco/snips-issues/issues/25
  * Posts: [1](https://medium.com/snips-ai/snips-air-a-private-by-design-open-source-decentralized-voice-assistant-a31e27fb799b)
* [Jasper](https://jasperproject.github.io/), code: https://github.com/jasperproject
  ![stars](https://img.shields.io/github/stars/jasperproject/jasper.svg?style=social)
* [Open Assistant](https://openassistant.org/), code: https://github.com/openassistant

## Video Surveillance

Many services tout "P2P" in video surveillance, to allow your smartphone to
connect to your camera - when you're in your home or on another side of the
world. That's oxymoron of course, there's nothing "point-to-point" in how
it's implemented. Both your camera and smarphone connect to faraway 3rd-party
cloud server (this happens even if both in the same home network, 5 meters
one from another). All video goes via (and thus to) 3rd party of course.

[Mirai Botnet](https://en.wikipedia.org/wiki/Mirai_(malware)) was/is a botnet
mostly consisting of video cameras controlled by 3rd party.


# Related/useful Services and Software

## Floor Plans

A step above and beyond dashboards is visualizing what happens where on the
actual floorplan of your home.

* [ha-floorplan](https://github.com/pkozul/ha-floorplan) - Floorplans for Home Assistant
* [Sweet Home 3D](https://sourceforge.net/projects/sweethome3d/) - Open Source
  desktop application
  ![Java Language][java-badge]
* https://planner5d.com - Online editor, allows to save/import plan in JSON
  format. Image renders are freemium.

## Related awesome lists

* [awesome-IoT](https://github.com/HQarroum/awesome-iot)
  ![stars](https://img.shields.io/github/stars/HQarroum/awesome-iot.svg?style=social)
* [awesome-IoT](https://github.com/phodal/awesome-iot) - bis
  ![stars](https://img.shields.io/github/stars/phodal/awesome-iot.svg?style=social)
* [awesome-home-automation](https://github.com/moodule/awesome-home-automation)
  ![stars](https://img.shields.io/github/stars/moodule/awesome-home-automation.svg?style=social)

## Other Awesome Lists

* [awesome-awesome](https://github.com/emijrp/awesome-awesome)
  ![stars](https://img.shields.io/github/stars/emijrp/awesome-awesome.svg?style=social)
* [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness)
  ![stars](https://img.shields.io/github/stars/bayandin/awesome-awesomeness.svg?style=social)
* [sindresorhus/awesome][awesome-link]
  ![stars](https://img.shields.io/github/stars/sindresorhus/awesome.svg?style=social)
* [The Warren](https://github.com/torchhound/warren)
  ![stars](https://img.shields.io/github/stars/torchhound/warren.svg?style=social)

# License

[![CC0][CC0-badge]][CC0-link]

To the extent possible under law, Paul Sokolovsky has waived all copyright
and related or neighboring rights to this work. See [LICENSE](LICENSE).

[awesome-badge]: https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg
[awesome-link]: https://github.com/sindresorhus/awesome
[CC0-badge]: http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg
[CC0-link]: https://creativecommons.org/publicdomain/zero/1.0/

[c-badge]: https://img.shields.io/badge/-C-blue.svg?style=flat&logo=c&colorA=grey
[cplusplus-badge]: https://img.shields.io/badge/-C%2B%2B-blue.svg?style=flat&logo=cplusplus&colorA=grey
[csharp-badge]: https://img.shields.io/badge/-C%23-blue.svg?style=flat&logo=csharp&colorA=grey
[groovy-badge]: https://img.shields.io/badge/-Groovy-blue.svg?style=flat&logo=groovy&colorA=grey
[java-badge]: https://img.shields.io/badge/-Java-blue.svg?style=flat&logo=java&colorA=grey
[javascript-badge]: https://img.shields.io/badge/-Js-yellow.svg?style=flat&logo=javascript&colorA=grey
[jquery-badge]: https://img.shields.io/badge/-JQuery-blue.svg?style=flat&logo=jquery&colorA=grey
[lua-badge]: https://img.shields.io/badge/-Lua-blue.svg?style=flat&logo=lua&colorA=grey
[perl-badge]: https://img.shields.io/badge/-Perl-red.svg?style=flat&logo=perl&colorA=grey
[php-badge]: https://img.shields.io/badge/-PHP-purple.svg?style=flat&logo=php&colorA=grey
[python-badge]: https://img.shields.io/badge/-Py-blue.svg?style=flat&logo=python&colorA=grey
