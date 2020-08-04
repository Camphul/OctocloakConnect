# OctoPrint-OctocloakConnect

Ability to integrate keycloak through vouch-proxy using nginx reverse proxy.

## Setup

Install via the bundled [Plugin Manager](https://docs.octoprint.org/en/master/bundledplugins/pluginmanager.html)
or manually using this URL:

    https://github.com/Camphul/OctocloakConnect/archive/master.zip

**TODO:** Describe how to install your plugin, if more needs to be done than just installing it via pip or through
the plugin manager.

## Configuration

```yaml
octocloakconnect:
    proxyIp: 192.168.1.1
    headers:
      user: X-Vouch-User
      authorization: Authorization

```
