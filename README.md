# Hugo WorkBox Module

This module mounts most of [WorkBox](https://github.com/GoogleChrome/workbox) packages on `assets/workbox-*` folder.

## Requirements

- Hugo `0.109.0` or above.
- [Hugo Module](https://gohugo.io/hugo-modules/use-modules/#prerequisite).

## Packages

> This module doesn't mount the `workbox-cli` and `workbox-webpack-plugin` packages.

> I didn't test all of the following packages, please [file an issue](https://github.com/razonyang/hugo-mod-workbox/issues/new) if you found one.

| Package | Path
|---|---
| `workbox-background-sync` | `assets/workbox-background-sync`
| `workbox-broadcast-update` | `assets/workbox-broadcast-update`
| `workbox-build` | `assets/workbox-build`
| `workbox-cacheable-response` | `assets/workbox-workbox-cacheable-response`
| `workbox-core` | `assets/workbox-core`
| `workbox-expiration` | `assets/workbox-expiration`
| `workbox-google-analytics` | `assets/workbox-google-analytics`
| `workbox-navigation-preload` | `assets/workbox-navigation-preload`
| `workbox-precaching` | `assets/workbox-precaching`
| `workbox-range-requests` | `assets/workbox-range-requests`
| `workbox-recipes` | `assets/workbox-recipes`
| `workbox-routing` | `assets/workbox-routing`
| `workbox-strategies` | `assets/workbox-strategies`
| `workbox-streams` | `assets/workbox-streams`
| `workbox-sw` | `assets/workbox-sw`
| `workbox-window` | `assets/workbox-window`

## Usage

```javascript
import { setCatchHandler, setDefaultHandler } from 'workbox-routing'
import { NetworkOnly } from 'workbox-strategies'
...
```
