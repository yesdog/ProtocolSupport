ProtocolSupport
===============

[![Chat](https://img.shields.io/badge/chat-on%20discord-7289da.svg)](https://discord.gg/x935y8p)
<span class="badge-paypal"><a href="https://www.paypal.com/cgi-bin/webscr?return=&business=true-games.org%40yandex.ru&bn=PP-DonationsBF%3Abtn_donateCC_LG.gif%3ANonHosted&cmd=_donations&rm=1&no_shipping=1&currency_code=USD" title="Donate to this project using Paypal"><img src="https://img.shields.io/badge/paypal-donate-yellow.svg" alt="PayPal donate button" /></a></span>

Support 1.14, 1.13, 1.12, 1.11, 1.10, 1.9, 1.8, 1.7, 1.6, 1.5, 1.4.7 clients on Spigot 1.14.3

WIP branch for adding MCPE clients support

Important notes:
* Only latest version of this plugin is supported
* This plugin can't be reloaded or loaded not at server startup
* This plugin doesn't work with netty native transport

Known issues:
* [Anything that is not latest] Items in creative mode may not work as expected, or may not work at all


Known wontfix issues:
* [1.12 and earlier] Chests are seen as enderchests. (Intentional to prevent rendering glitches!)  
[Check this plugin if you want different behaviour](https://www.spigotmc.org/resources/protocolsupportchestfix.59314/)
* [1.8 and earlier] Thrown potion texture is invalid
* [1.8 and earlier] Can't control vehicle
* [1.6 and earlier] Stats are not sent
* [1.4.7] Server shows up as "incompatible" in the server list, impossible to fix due to the lack of an way to verify the client version during server list ping

---

Website: https://protocol.support/

Spigot: https://www.spigotmc.org/resources/protocolsupport.7201/

BukkitDev: https://dev.bukkit.org/projects/protocolsupport/

MC Market: http://www.mc-market.org/resources/4607/

Jenkins: https://build.true-games.org/job/ProtocolSupport/

---

Licensed under the terms of GNU AGPLv3
