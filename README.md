![plentymarkets Logo](http://www.plentymarkets.eu/layout/pm/images/logo/plentymarkets-logo.jpg)

# Shipping service provider template plugin for plentymarkets

Use this repository by forking it and editing the following files:

### `src/Helpers/ShippingServiceProvider.php`
- constant `PLUGIN_NAME` defines the name of your new plugin (should be the same as namespace)
- constant `SHIPPING_SERVICE_PROVIDER_NAME` is used to define your shipping provider name

---

### `plugin.json`
#### (optional)
- edit `name` to match your root folder name
- edit `namespace` to match your `name`

**NOTE**: Namespace change requires all class files to be updated with the new namespace

More info about `plugin.json` file can be found [here](https://developers.plentymarkets.com/en-gb/developers/main/plugin-definition.html)
