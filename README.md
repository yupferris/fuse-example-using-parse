# Using Parse with Fuse Example
A basic (and obsolete) example showing how to use Parse with Fuse. This is a super simple app using [Parse](https://www.parse.com) as a backend service, where anyone can simply post text, and anyone else can see that text. All relevant code is in the `MainView.ux` file.

Note: This example has also been ported to use [Syncano](https://www.syncano.io/) in [@bolav](https://github.com/bolav)'s fork: https://github.com/bolav/fuse-example-using-syncano , and there's also a version running on [back4app](https://github.com/tim-hub/fuse-example-using-back4app-parse) ported by [@tim-hub](https://github.com/tim-hub) !

## Setup
You'll need to use your own Parse app backend with this example. Insert your app's Application ID and Javascript Key into the `api-keys.js` file:
```js
module.exports = {
	appId: "YOUR APP ID HERE",
	jsKey: "YOUR JS KEY HERE"
};
```

Once that's done, you're ready to roll!

## Fuse version
This example was produced with Fuse (beta) v0.8.4.

## Branches
The "finished product" is on the `master` branch, and the template I started with in the video is on the `starting-template` branch.

## License
This code is licensed under the BSD2 license (see LICENSE). The Parse JavaScript SDK v1.6.7 is licenced under its own BSD-style license (see parse-1.6.7.js).
