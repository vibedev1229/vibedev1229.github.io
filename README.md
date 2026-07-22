# vibedev1229.github.io

Developer site root for **VibeDeV** / **VIBECORE DIGITAL**.

This repo exists so that `https://vibedev1229.github.io/app-ads.txt` resolves at the **domain
root**, which is where the [IAB Tech Lab app-ads.txt spec](https://iabtechlab.com/ads-txt/)
requires it. Ad crawlers do not look in subdirectories — a project Pages site such as
`vibedev1229.github.io/app-ads/` is **not** a valid location and will fail AdMob verification.

`app-ads.txt` declares the authorized sellers of ad inventory for every VibeDeV Android app
(Brain Bolt, Brawl Toons, Faresight, Hyper Bounce, Lumenroot, Tappy Bird). All six share one
AdMob publisher ID, so this single file covers all of them.

Each app's Google Play listing must keep its **Website** field on this domain for AdMob to
crawl this file.
