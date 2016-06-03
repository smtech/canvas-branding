# Branding

A record of our current branding configuration via the Canvas Theme Editor.

For what it's worth, our [`brand_config.json`](https://github.com/smtech/canvas-branding/blob/master/brand_config.json) document is automagically generated for us by Canvas (woo hoo!). It uses some variables in the JavaScript environment, so, to get the latest version, I open the JavaScript console in developer view of my browser and fire off the following snippet:

```JavaScript
window.location.href = (ENV.ASSET_HOST + ENV.active_brand_config_json_url)
```

This gets me the actual document (which I pretty print for readability).
