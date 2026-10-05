# Movi.me Privacy Policy

**Last updated: October 5, 2026**

This policy covers the Movi.me apps for **iPhone, iPad and Apple TV** ("the App"). Movi.me is a personal video library: it organises and plays videos that you supply — from your device, your drives, or a media server you run yourself. We wrote the App so that your data stays with you.

## The short version

- Movi.me has **no accounts server, no cloud, no analytics, no advertising SDKs and no tracking.**
- Everything the App knows — accounts, settings, watch progress, lists — is stored **on your device**.
- The App talks to outside services only to fetch **movie information, artwork and subtitles**, and only with **API keys you provide**. They receive titles or IDs, never anything about you.

## 1. Data stored on your device

The App stores the following locally, on the iPhone, iPad or Apple TV where you use it:

- **Accounts** — usernames, roles and password hashes (passwords are never stored in plain text). Accounts exist only on that device.
- **Your library** — titles, descriptions, ratings, posters, episode details, playlists, Watch.me lists, Live TV channels, chapters and clips.
- **Viewing history** — playback positions for Continue Watching, and recently watched titles and shows used for recommendations ("For You").
- **Settings** — language, theme, parental controls, media server addresses and your API keys.

**Apple TV:** tvOS may clear an app's storage when the device runs low on space. To survive that, the Apple TV app keeps a copy of accounts, settings, watch progress, Watch.me lists and playlists in the app's own system preferences storage **on the same Apple TV**. It also shares a short list of in-progress titles with its Top Shelf extension on the same device, so they appear on the Apple TV Home Screen. None of this leaves the device.

We (the developer) never receive any of this data.

## 2. Your media servers

If you add a media server, the App connects directly from your device to the address you enter — on your home network, or through a VPN such as Tailscale — to list and stream your files. That traffic goes only between your device and your server. If you use a VPN, the VPN provider's own policy applies to that connection.

## 3. Third-party services

The App contacts these services directly from your device, using API keys **you** enter in the App. Each receives only what it needs:

| Service | When | What is sent |
|---|---|---|
| **OMDb API** (omdbapi.com) | Fetching movie and show information | A title (and year) or an IMDb ID |
| **TMDB** (themoviedb.org) | Fetching artwork, translations, episode details and trailer references | An IMDb ID or TMDB ID, season and episode numbers, and the language |
| **OpenSubtitles** (opensubtitles.com) | Only when you search for or download subtitles | A title or IMDb ID, season and episode numbers, and the language |
| **YouTube** (iPhone/iPad only) | Only when you watch a trailer | The trailer plays in YouTube's embedded player; Google's privacy policy applies |

No personal information, account details, viewing history or device identifiers are sent to these services. Their own privacy policies govern how they handle the requests.

**Saving social media reels (iPhone/iPad).** When you share or paste a link to an Instagram, TikTok or YouTube post, the App fetches that public post page to read its caption, author handle and thumbnail, and saves them with the link in your library. The video itself is not downloaded from the platform.

## 4. Device permissions

The App asks for these only when you use the matching feature:

- **Photo Library** — to import videos you choose, and to save videos you export.
- **Files** — to import videos from the Files app, drives and other locations you pick.
- **Local Network** — to find and stream from media servers on your home network, and for **Watch in another room**, which finds other Movi.me devices (Apple TV, iPhone, iPad) on the same home network and keeps them on the same title and spot. Those messages (which title, play/pause, position) travel only across your home network.
- **Speech Recognition** (iPhone/iPad) — to turn a video's narration into notes. Recognition runs **on the device**; audio is not sent anywhere.

**SharePlay and AirPlay** are optional. SharePlay (iPhone, iPad and Apple TV) shares playback state — which title (its name, IMDb ID and your media server's address for it), position, play/pause — with the people in your FaceTime call through Apple's SharePlay service. AirPlay sends the video stream to the receiver you choose.

## 5. Analytics, advertising and tracking

The App collects **no analytics, usage data, crash reports or telemetry**, contains **no third-party advertising or tracking code**, and does **not track you** across apps or websites. The App's "Ad Studio" only plays promotional clips that you or your household add to your own library.

## 6. Children

Movi.me includes device-wide parental controls that let an administrator limit content by rating (G, PG, PG-13, R, NC-17). The App does not collect data from anyone, including children.

## 7. Deleting your data

- **Clear All Data** (Admin) removes everything the App stores on that device.
- Deleting a user (Admin → Users) removes that account and its history.
- Deleting the App removes all of its data from the device.

Because nothing is stored with us, there is nothing for us to delete on our side.

## 8. Changes to this policy

If this policy changes, the new version will be published here with a new "Last updated" date, and the App's built-in policy will be updated in the next release.

## 9. Contact

Questions about this policy? Use the support link on the App Store listing, or [open an issue in this repository](https://github.com/petro-benjamin/Movi.me-Privacy-Policy/issues).

---

### Credits

- This product uses the TMDB API but is not endorsed or certified by TMDB.
- Movie information is provided by the OMDb API (omdbapi.com). Movi.me is not endorsed by or affiliated with OMDb.
- Subtitles are provided by OpenSubtitles.com. Movi.me is not endorsed by or affiliated with OpenSubtitles.
- Tailscale is a trademark of Tailscale Inc. Movi.me is not affiliated with or endorsed by Tailscale.
- Apple, Apple TV, iPhone, iPad, AirPlay and SharePlay are trademarks of Apple Inc.
