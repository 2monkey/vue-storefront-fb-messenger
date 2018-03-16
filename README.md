# vue-storefront-fb-messenger
[Customer Chat Facebook Plugin](https://developers.facebook.com/docs/messenger-platform/discovery/customer-chat-plugin)

# Setup

The enabled extensions must be declared within config/local.json file. Please take a look at the default config for a reference.

You should just add your extension name to:

```javascript
 "registeredExtensions": ["fb-customer-chat"]
```

# Config

Add this to your config

```javascript
    "fbchat": {
      "id": your-fb-page-id
    },
```
