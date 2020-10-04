# home-assistant-awair-local-polling-configuration

This is a simple `configuration.yaml` script that connects your home assistant to Awair in LAN mode.

**In order to get it working, you'll need to :**
1. Enable Awair's [Local Sensor Mode](https://support.getawair.com/hc/en-us/articles/360049985053-What-is-the-Local-Sensors-feature-)
2. Find the IP address that your router gave to your sensor by looking up your Awair's mac address on your router's home page
3. Preferably switch that devices IP address to a static one from your router's home page/settings
4. Copy the configurations from [the example script](/configuration.yaml) in this repo into your `<config_dir>/configuration.yaml` file on your Home Assistant

bpowers made a [built-in version of this](https://github.com/home-assistant/core/pull/39538) that would come ready made in hass.io. It serves the same purpose and it would be readily available in Hassio once they approve of their code.
