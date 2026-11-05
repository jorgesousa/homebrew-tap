# homebrew-tap

Homebrew formulas for [neteinstein](https://github.com/neteinstein)'s projects.

## [Calendar Sync](https://github.com/neteinstein/Calendar-Sync)

A tiny macOS menu bar app that copies meetings from your client calendars into your main
calendar. The formula builds it from source on your Mac (needs macOS 14+ and the Xcode 15+
command line tools).

```bash
brew install neteinstein/tap/calendar-sync
open "$(brew --prefix)/opt/calendar-sync/Calendar Sync.app"
```

`brew install --HEAD neteinstein/tap/calendar-sync` builds the latest `main` instead of the
pinned version. Update with `brew update && brew upgrade calendar-sync`.

## [ONAIR](https://github.com/jorgesousa/onair)

Just TV. An IPTV player for macOS with no ads, no watermarks, no accounts and no tracking.
The formula builds it from source on your Mac (needs macOS 14+ and the Xcode command line tools).

```bash
brew install jorgesousa/tap/onair
open "$(brew --prefix)/opt/onair/OnAir.app"
```

ONAIR tells you when a new version is out. Update with `brew update && brew upgrade onair`.
