# Speedport Integration for Home Assistant

[![release][release-badge]][release-url]
![downloads][downloads-badge]
[![PayPal.Me][paypal-me-badge]][paypal-me-url]
[![BuyMeCoffee][buy-me-a-coffee-shield]][buy-me-a-coffee-url]

Telekom Speedport Integration for Home Assistant based
on [speedport-api](https://github.com/Andre0512/speedport-api.git).

## Introduction

First a few words to start with. A big thank you goes to @Andre0512 (https://github.com/Andre0512/speedport), who initially launched the card, but he does not have enough time for further care. I forked this card for my own HomeAssistant to make a few improvements. I give no guarantee for the functionality and no promise of lifelong maintenance, as I do the whole thing in my free time. Of course, I am happy about every contribution and PR


## Features

- Track presence of connected devices
- Turn on/off wifi (guest/office/normal)
- Reconnect, reboot, wps on
- Sensors (IP-Addresses, Upload/Download, Connection, ...)

## Supported devices

* Speedport Smart 3
* Speedport Smart 4

## Installation

### HACS

The Speedport is not available in [HACS][hacs] (Home Assistant Community Store) by default, but you can add it as custom repositories.

1. Install HACS if you don't have it already
2. Open HACS in Home Assistant 
3. Add this repository (https://github.com/MelleD/speedport) via HACS Custom repositories ([How to add Custom Repositories](https://hacs.xyz/docs/faq/custom_repositories/))

[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=MelleD&repository=speedport&category=integration)

### Manuall (not recommended)

Manually copy `speedport` folder from [latest release](https://github.com/MelleD/speedport/releases/latest) to `config/custom_components` folder.

_Restart Home Assistant_

## Configuration

**Method 1**: [![Open your Home Assistant instance and start setting up a new integration.](https://my.home-assistant.io/badges/config_flow_start.svg)](https://my.home-assistant.io/redirect/config_flow_start/?domain=speedport)

**Method 2**: Settings > Devices & Services > Add Integration > **Speedport**  
_If the integration is not in the list, you need to clear the browser cache._

### Further Information

If you have email notifications enabled, make sure you have the "A security related event has occurred" option unchecked or you will receive a lot of emails.

## Support

Clone and create a PR to help make the card even better.

Please ⭐️ or sponsor this repo when you like it.

## Sponsor ❤️

<a href="" target="_blank"><img src="https://img.shields.io/static/v1.svg?label=%20&message=PayPal.Me&logo=paypal" alt="PayPal.Me MelleDennis" style="height: auto !important;width: auto !important;" ></a>

<a href="https://www.buymeacoffee.com/melled" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/white_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>



<!-- Badges -->

[hacs-badge]: https://img.shields.io/badge/hacs-default-orange.svg?style=flat-square
[release-badge]: https://img.shields.io/github/v/release/MelleD/speedport?style=flat-square
[downloads-badge]: https://img.shields.io/github/downloads/MelleD/speedport/total?style=flat-square
[build-badge]: https://img.shields.io/github/actions/workflow/status/MelleD/speedport/build.yml?branch=main&style=flat-square
[paypal-me-badge]: https://img.shields.io/static/v1.svg?label=%20&message=PayPal.Me&logo=paypal
[buy-me-a-coffee-shield]: https://img.shields.io/static/v1.svg?label=%20&message=Buy%20me%20a%20coffee&color=6f4e37&logo=buy%20me%20a%20coffee&logoColor=white

<!-- References -->

[hacs-url]: https://github.com/hacs/integration
[home-assistant]: https://www.home-assistant.io/
[hacs]: https://hacs.xyz
[release-url]: https://github.com/MelleD/speedport/releases
[paypal-me-url]: https://www.paypal.me/MelleDennis
[buy-me-a-coffee-url]: https://www.buymeacoffee.com/melled