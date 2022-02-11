---
title: History
layout: default
---

<h1 id="v0.1.3">v0.1.3</h1>
<small>2022-02-11</small>

Small release that brings back the "all items" feed (but it now correctly works when you have both *podcasts* and *blogs*) and brings back the feature that showed the feed type.

Also:

* Case insensitive sorting of feeds

<h1 id="v0.1.2">v0.1.2</h1>
<small>2022-02-09</small>

This is the first public release on the [Umbrel](http://getumbrel.com) app store.

Changes:

* A couple of bugfixes in the way we deal with podcast feeds

<h1 id="v0.1.1">v0.1.1 (Booster)</h1>
<small>2022-02-04</small>

This is the first public release on the [Citadel](https://github.com/runcitadel) app store.

Changes:

* Send boosts and streaming contributions to podcast creators (that use the `podcast:value` tag)
* Save the play position (per-episode!) in the database, so you always listen from where you left off (even if you're using multiple devices!)
* Save volume in the database
* Fetch feeds automatically in the background
* Dark mode
* Lots of fixes and UI improvements

<h1 id="v0.1.0">v0.1.0 (Runs on ARMs)</h1>
<small>2022-01-12</small>

This is the first time **usocial** runs on **an ARM-based machine** (my [Umbrel](https://getumbrel.com/) running on a Raspberry Pi 4). Before this I was running it directly on my laptop.

Features:

* Subscribe to blogs via RSS/Atom
* Search & subscribe to podcasts from [Podcast Index](https://podcastindex.org)
* Play podcasts in browser
* Parse the [podcast:value](https://github.com/Podcastindex-org/podcast-namespace/blob/main/value/value.md) tag and keep track of the amount of time listened for podcasts using this tag (see [karma](/karma))
* Fever-like [API](/api)
