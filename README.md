Invid is an iOS app for [Invidious](https://github.com/iv-org/invidious), a privacy-focused (and discontinued) front-end to YouTube.

Invid uses the Invidious API to fetch and play videos. You can use the share sheet extension to open compatible video URLs. The app also scans for compatible URLs in your pasteboard. There is an optional in-app web view for browsing videos.

This app was a personal learning project intended for personal use, so the UI is quite bland. Development is now stopped due to [the unclear future of Invidious](https://github.com/iv-org/invidious/issues/1320). I'm releasing this to get some sense of accomplishment during Covid. No updates are promised.

While the official Invidious instance is shutting down on September 1st, you can switch to [other public instances](https://github.com/iv-org/invidious/wiki/Invidious-Instances) so the app should continue to work until breaking changes are made to YouTube.

**Features**

-	based on stock video player (AVPlayerViewController)
-	no ads and data collection
-	Smart Rotate - watch videos in landscape regardless of Portrait Orientation Lock
-	background playback
-	stream audio track only
-	default resolution (up to 1080p) for cellular, VPN, and Wi-Fi
-	default subtitle languages
-	disable high frame rate content
-	playback rate adjustment at 0.05x intervals
-	double tab and hold to forward / back 15 seconds

**Known bugs**

-	Buggy Airplay
- Subtitles disappear after resuming from background (switch video resolution then they reappear)

**Not supported**

- iOS 11 and below
-	iPad
-	playlists
-	timestamps

**Download**

[https://github.com/cclhk/Invid/releases/download/v0.1.2/Invid.v0.1.2.ipa](https://github.com/cclhk/Invid/releases/download/v0.1.2/Invid.v0.1.2.ipa)

Use [Xcode and iOS App Signer](https://old.reddit.com/r/jailbreak/wiki/xcodeiosappsigner) (macOS), or [AltStore](https://old.reddit.com/r/jailbreak/wiki/altstore) (Windows & macOS) to install.
___
If you like the app, consider contributing to [Invidious](https://github.com/iv-org/invidious), standing with [Hong Kong](https://twitter.com/ProtonVPN/status/1301064825053818887), or joining [#BoycottMulan](https://www.nytimes.com/2019/08/16/world/asia/boycott-mulan.html).
