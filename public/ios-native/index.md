---
title: Native iOS app, version 1.1
date: 2026-10-15
---

BARTist version 1.1 is now an iOS native app implemented in Swift.

<p><a class="app-store" href="https://apps.apple.com/us/app/bartist/id6816738607"><img src="/assets/download-on-the-app-store.svg" alt="Download on the App Store" width="120" height="40"></a></p>

The [first App Store release](../ios-app/) was written using the cross platform [Tauri](https://tauri.app/) framework. It worked well, but fell just a bit short of other native apps - pull to refresh, tabs, pinch to zoom were just a bit clunkier and less fitting. It's time for a real native iOS app. Given that BARTist is simple, so was the rewrite.

The trains tab provides the same dense view of real time train departure information grouped by destination. Note the native tabs and buttons. Also, it now supports the same pull to refresh feel you expect in iOS apps:

![Train departures at Embarcadero](./bartist-trains-ios-native.png)

Station picker also has a native iOS look and now supports gestures for closing the selection modal:

![Station picker](./bartist-stations-ios-native.png)

And the system map, still with the day/night toggle, gives you a buttery smooth pinch to zoom:

![BART system map](./bartist-map-ios-native.png)

The same app, better UX. Still no ads, accounts, subscriptions, tracking, or analytics. It's open source and the [code is on GitHub](https://github.com/unix1/bartist). Enjoy!
