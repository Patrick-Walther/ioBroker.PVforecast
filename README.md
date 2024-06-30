![Logo](admin/pvforecast.png)

# ioBroker.pvforecast

[![NPM version](https://img.shields.io/npm/v/iobroker.pvforecast?style=flat-square)](https://www.npmjs.com/package/iobroker.pvforecast)
[![Downloads](https://img.shields.io/npm/dm/iobroker.pvforecast?label=npm%20downloads&style=flat-square)](https://www.npmjs.com/package/iobroker.pvforecast)
![node-lts](https://img.shields.io/node/v-lts/iobroker.pvforecast?style=flat-square)
![Libraries.io dependency status for latest release](https://img.shields.io/librariesio/release/npm/iobroker.pvforecast?label=npm%20dependencies&style=flat-square)

![GitHub](https://img.shields.io/github/license/iobroker-community-adapters/iobroker.pvforecast?style=flat-square)
![GitHub repo size](https://img.shields.io/github/repo-size/iobroker-community-adapters/iobroker.pvforecast?logo=github&style=flat-square)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/iobroker-community-adapters/iobroker.pvforecast?logo=github&style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/iobroker-community-adapters/iobroker.pvforecast?logo=github&style=flat-square)
![GitHub issues](https://img.shields.io/github/issues/iobroker-community-adapters/iobroker.pvforecast?logo=github&style=flat-square)
![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/iobroker-community-adapters/iobroker.pvforecast/test-and-release.yml?branch=main&logo=github&style=flat-square)

## Versions

![Beta](https://img.shields.io/npm/v/iobroker.pvforecast.svg?color=red&label=beta)
![Stable](http://iobroker.live/badges/pvforecast-stable.svg)
![Installed](http://iobroker.live/badges/pvforecast-installed.svg)

Provides forecast data from [forecast.solar](https://forecast.solar), [Solcast](https://solcast.com/) or [SolarPredictionAPI](https://rapidapi.com/stromdao-stromdao-default/api/solarenergyprediction/)

## Documentation

[🇺🇸 Documentation](./docs/en/README.md)

[🇩🇪 Dokumentation](./docs/de/README.md)

## Credits

- Logo (Sun): https://pixabay.com/de/vectors/sonne-wetter-wettervorhersage-157126/

## Sentry

**This adapter uses Sentry libraries to automatically report exceptions and code errors to the developers.** For more details and for information how to disable the error reporting see [Sentry-Plugin Documentation](https://github.com/ioBroker/plugin-sentry#plugin-sentry)! Sentry reporting is used starting with js-controller 3.0.

## Changelog
<!--
    Placeholder for the next version (at the beginning of the line):
    ### **WORK IN PROGRESS**
-->
### 3.0.0 (2024-06-30)

NodeJS >= 18.x and js-controller >= 5 is required

* (klein0r) Load system configuration via parameter
* (coltc50) Added damping factor for forecast solar

### 2.9.1 (2023-12-18)
* (klein0r) Avoid logging of api key

### 2.9.0 (2023-10-28)
* (klein0r) Updated conversion for Solcast
* (klein0r) Store JSON state values in prettified format

### 2.8.2 (2023-10-28)
* (klein0r) Added icons in admin tabs

### 2.8.1 (2023-09-16)
* (klein0r) Fixed graph limits in summary
* (klein0r) Added options for summary graph and label color

## License
MIT License

Copyright (c) 2021-2024 Patrick-Walther
                        Matthias Kleine <info@haus-automatisierung.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
