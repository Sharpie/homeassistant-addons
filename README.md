HomeAssistant Addons
====================

This repository contains add-ons for the [HomeAssistant home automation server][hass].

[hass]: https://www.home-assistant.io/

## Add-ons

This repository contains the following add-ons:

[aarch64-yes]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-yes]: https://img.shields.io/badge/amd64-yes-green.svg

[armhf-no]: https://img.shields.io/badge/armhf-no-red.svg
[armv7-no]: https://img.shields.io/badge/armv7-no-red.svg
[i386-no]: https://img.shields.io/badge/i386-no-red.svg

### [Selenium Standalone Firefox](./selenium-ff)

![Supports aarch64 Architecture][aarch64-yes]
![Supports amd64 Architecture][amd64-yes]
![Does not support armhf Architecture][armhf-no]
![Does not support armv7 Architecture][armv7-no]
![Does not support i386 Architecture][i386-no]

This add-on runs the [Selenium browser automation server][selenium] in a
container where the Firefox browser is also installed. Connections to
the server can be made on port 4444 by a client, such as the
[`selenium` python library][selenium-python]. This is useful for integrations
that need to execute some workflow that only functions in a full browser
environment, usually due to the need for executing JavaScript.

[selenium]: https://www.selenium.dev/
[selenium-python]: https://pypi.org/project/selenium/
