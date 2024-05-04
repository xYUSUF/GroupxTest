# Gamek's Proxyless Group Finder
Gamek's Group Finder is currently the best finder out there, featuring unique method of bypassing ratelimits. Other finders required proxies to work, but this only requires a little bit of Roblox cookies.
# Why is it the best group finder out there right now?

Let's get this quick. Basic Group Finder only does **200 requests** per **1 proxy**. But cookies can do impressing **2.000 requests** per **1 cookie**. This makes running good finder **easier**, since good proxies cost a lot of money, but cookies - literally nothing.

You see the difference now?i
## How to install this?

This should be pretty simple. This finder requires:
* Python
* Good PC, or VPS

### Python
Installing Python is easy process, go to [python.org](https://www.python.org/downloads/), and proceed with installing. Recommended version to run this finder is `Python 3.10`.


After that, install this repository, and extract it any folder. Thats basically all you need to do in this section.
## You need to make sure to have this  edited!
If you are using `Linux` version, at the top you will have those variables:
```py
LOG=''
GROUP='' 
SPECS='(16 cores HETZNER)'
```

Variable `log` is what your finder going to use as method of saying CPS, checked groups and etc. At first, you need to send some message from your webhook, then copy this message, and after your webhook URL you should paste `/<mesaage id>`. Something like this should end up: `https://discord.com/webhooks/12345/gooberish/67890`

Variable `Group` is where your finder gonna send groups. You just need your webhook. Something like this should end up: `https://discord.com/webhooks/12345/gooberish`

Variable `Specs` are basically useless and is created for no reason whatsoever. You can put here your VPS stats idk. 🤷‍♂️
## Requirements list
In order to make this work, you need to install those modules:

```
multiprocessing
time
requests
json
threading
multiprocessing
aiohttp
```
To install module, you need to run `pip install [module]`. Some of them are already preinstalled, some are not. Original creator have **0 idea** about how `pip freeze` works.

## Support

If you encounter any issues while using this Group Finder, feel free to DM me on Discord, ` @gamek989`.


## Authors

* original re----ed code is made by gamek
* better readme.md is made by me, mehhovcki
