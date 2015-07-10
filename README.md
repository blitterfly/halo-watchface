# Halo Watchface (Pebble Time)

Simple watchface with a Halo logo and updates from the latest @Halo Twitter feed.

## Dependencies

 * [Pebble SDK 3.0](http://developer.getpebble.com/sdk/)
 * [UglifyJS 2](https://github.com/mishoo/UglifyJS2)
 * [CryptoJS](https://code.google.com/p/crypto-js/) (included in repository)
 
## Building

Note: The API secrets for interfacing with the Twitter API are stored in a file called `src/js/secrets.js`. This is not included in the repository, so you will need to create your own and defined the
following JavaScript variables:

 * CONSUMER_KEY
 * CONSUMER_SECRET
 * ACCESS_TOKEN
 * ACCESS_SECRET

## License

The code is licensed under the [CC0 1.0 universal license](LICENSE.md) and based off of the [watchface tutorial](https://github.com/pebble-examples/watchface-tutorial).

Includes [CryptoJS](https://code.google.com/p/crypto-js/) licensed under the [MIT license](https://code.google.com/p/crypto-js/wiki/License).

Halo® is a registered trademark of Microsoft Corp. Not affiliated in any way with the creator of this watchface.