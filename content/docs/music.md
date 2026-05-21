---
title: "Music"
weight: 20
---

# Music

Stream music from the Farmhouse server. The library has a wide collection you can listen to from anywhere.

**Open the app:** [music.tyhurstfarmhouse.com](https://music.tyhurstfarmhouse.com)

> [!NOTE]
> **First time on this device?** You'll see a Cloudflare security screen before the login -- enter your email and the 6-digit code it sends you. See [Your first login]({{< relref "/docs/getting-started#your-first-login" >}}).

## On your computer

1. Go to [music.tyhurstfarmhouse.com](https://music.tyhurstfarmhouse.com).
2. Log in with your **Farmhouse username and password** -- the same login you use for the other apps. If it doesn't work, you may not have been added to the music app yet; email Corey.
3. Browse by artist, album, genre, or use the search bar.

## On your phone

The web player works on mobile, but dedicated apps give a better experience. The music server (Navidrome) works with any app that supports the **Subsonic** protocol:

### Recommended apps

| Platform | App | Cost |
|---|---|---|
| **Android** | [Symfonium](https://play.google.com/store/apps/details?id=app.symfonium) | Paid (one-time, worth it) |
| **Android** | [DSub](https://play.google.com/store/apps/details?id=github.daneren2005.dsub) | Free / Paid |
| **iPhone** | [play:Sub](https://apps.apple.com/us/app/play-sub-music-streamer/id955329386) | Paid |
| **iPhone** | [Amperfy](https://apps.apple.com/us/app/amperfy-music/id1530145038) | Free |

### Setting up a music app

When any app asks for server details:
- **Server:** `https://music.tyhurstfarmhouse.com`
- **Username / Password:** Your Farmhouse username and password.

{{< details "App won't connect?" >}}
Some Subsonic apps ask for an API path. Try `https://music.tyhurstfarmhouse.com` on its own first; if the app won't connect, add `/rest` to the end of the server address.
{{< /details >}}

## Good to know

- You can create playlists, star your favorites, and the app tracks your listening history.
- Music downloads for offline listening are supported by most of the apps listed above.
- The library is regularly updated with new music.
