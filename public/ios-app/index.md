---
title: BARTist is on the App Store!
date: 2026-10-08
---

BARTist is back! This time for iPhone.

<p><a class="app-store" href="https://apps.apple.com/us/app/bartist/id6816738607"><img src="/assets/download-on-the-app-store.svg" alt="Download on the App Store" width="120" height="40"></a></p>

It does what I want on my commute: display live BART train departure times. Pick a station, see next few trains by destination with car length and minutes until each departure.

![Train departures at Embarcadero](/bartist-trains.png)

What do I mean by being back? Read its history.

First, I [wrote it for Ubuntu Touch](../history-ubuntu-touch/) but then Canonical shut down their entire mobile ecosystem.

Later I [rewrote it for Android](../history-android-qml/) using QML/QtQuick but after some time Google pulled it from Play Store for a missed minor OpenSSL patch.

And now BARTist has its third home on Apple's App Store, staying true to its original UX.

This is the station picker on iPhone.

![Station picker](/bartist-stations.png)

And here is the system map, with the day/night toggle for respective service coverage.

![BART system map](/bartist-map.png)

It uses [BART's official API](https://www.bart.gov/schedules/developers/api). No ads, accounts, subscriptions, tracking, or analytics. The [code is on GitHub](https://github.com/unix1/bartist). Feedback and contributions are welcome.
