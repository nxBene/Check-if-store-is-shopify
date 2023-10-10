Sure, here's the corrected text in proper English:

## Check if a Store is Hosted on Shopify

By [github.com/nxBene](https://github.com/nxBene)

### Installation

1. Create a new bookmark and name it whatever you prefer.
2. In the "URL" field, insert the following code:

```javascript
javascript:(function(){  var currentURL = window.location.href;  var newURL = currentURL.split('/').slice(0, 3).join('/') + '/admin';  window.location.href = newURL;})();
```

### Usage

If you are on a website that you suspect is hosted on Shopify, simply click the bookmark. You will be redirected if the website is indeed a Shopify store.

### Contributing

Pull requests are welcome. For significant changes, please open an issue first to discuss what you would like to modify.

Please report any bugs or share ideas on my [Discord](https://discord.gg/FXRuVCFguJ).

### License

[MIT](https://choosealicense.com/licenses/mit/)

Let me know if you need any further assistance!
