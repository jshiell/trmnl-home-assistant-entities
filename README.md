# TRMNL Home Assistant Entities

A plugin to view home assistant entities on a [TRMNL](https://usetrmnl.com) device.

![A screenshot of the recipe running on trmnl-preview](screenshot.jpg)

## Prerequisites

You'll need:

* A publicly-accessible [Home Assistant](https://www.home-assistant.io) server (i.e. from the public internet, if you're using usetrmnl.com, or to your server if in a BYOS environment). If public, the easiest way to do this is via [Home Assistant Cloud](https://www.home-assistant.io/cloud/).
* A long-lived access token for your server, which you can generate from [your profile on the Security tab](https://my.home-assistant.io/redirect/profile).

## Running Locally

You'll need Ruby to run [trmnl-preview](https://github.com/usetrmnl/trmnlp) or Docker.

```bash
HOME_ASSISTANT_ACCESS_TOKEN=<your long-lived access token here> bin/trmnlp serve
```
