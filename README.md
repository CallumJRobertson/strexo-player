# StrexoPlayer

<a href="https://github.com/sponsors/CallumJRobertson">
  <img src="https://img.shields.io/badge/GitHub%20Sponsors-Support%20Me-%23ea4aaa?style=for-the-badge&logo=githubsponsors&logoColor=white" />
</a>
<a href="https://ko-fi.com/F1F01WXQS8">
  <img src="https://ko-fi.com/img/githubbutton_sm.svg" />
</a>

**A neutral media player with connected tracking, metadata, source, intro skip, and anime skip APIs.**

StrexoPlayer is a lightweight, high-quality media player for iOS and Android TV. It is built to make playback feel faster, cleaner, and more capable while integrating with the services people already use to track watching and improve playback.

It is not centered on one ecosystem. StrexoPlayer supports multiple APIs side by side, including Trakt, Simkl, AniList, the Stremio API, IntroDB, TheIntroDB, and AniSkip.

---

## Features

- Fast, reliable media playback
- Stream switching from inside the player
- Subtitle controls
- Advanced audio controls, including delay adjustment
- Android TV optimized UI and remote controls
- Native iOS playback with broad format support
- Tracking integrations for Trakt, Simkl, AniList, and the Stremio API
- Intro and anime skip support through IntroDB, TheIntroDB, and AniSkip
- Ongoing improvements based on community feedback

---

## Integrated APIs

StrexoPlayer currently integrates with:

- **Trakt** for watch progress, history, and scrobbling workflows
- **Simkl** for connected watch-state and history workflows
- **AniList** for anime tracking workflows
- **Stremio API** as one supported source and progress API
- **IntroDB** for intro skip timing data
- **TheIntroDB** for additional intro skip coverage
- **AniSkip** for anime opening and ending skip data

You only need to connect the services you use.

---

## Platforms

- **iOS:** available through TestFlight
- **Android TV:** available as an APK
- **Apple TV:** closed beta through Discord
- **Android mobile:** in development

---

## Status

StrexoPlayer is actively in development.

Most core playback functionality is stable, but the app is still moving quickly. You may run into bugs, edge cases, or format-specific playback issues. Reports are genuinely useful and help shape the app.

---

## Testing And Feedback

If you notice anything off, please open an issue or drop a message in Discord.

Useful reports include:

- Playback issues
- Tracking or sync problems
- Intro skip or anime skip mismatches
- UI bugs
- Device-specific playback problems
- Dolby Vision or HDR issues

Please include your platform, device model, connected services involved, and what you expected to happen.

---

## Known Limitations

- Some stream types and formats are still being improved
- Dolby Vision support is not fully complete yet
- Tracking accuracy can depend on how well an item matches across connected services
- Skip controls only appear when matching IntroDB, TheIntroDB, or AniSkip timing data is available

---

## Setup

Basic flow:

1. Install StrexoPlayer on your device.
2. Open the app and connect the APIs you use.
3. Start playback from your preferred source or workflow.
4. Confirm tracking, subtitles, stream switching, and skip controls behave as expected.

Detailed guides:  
https://strexo.space

---

## Support

If you want to support development:

<a href="https://github.com/sponsors/CallumJRobertson">
  <img src="https://img.shields.io/badge/GitHub%20Sponsors-Support-%23ea4aaa?logo=githubsponsors&logoColor=white" />
</a>
<a href="https://ko-fi.com/F1F01WXQS8">
  <img src="https://ko-fi.com/img/githubbutton_sm.svg" />
</a>

No pressure. Using the app, reporting issues, and sharing good bug reports helps a lot.

---

## Credits

- Trakt, Simkl, AniList, Stremio, IntroDB, TheIntroDB, and AniSkip ecosystems
- Community testers and contributors
- Logo/design by `<YOUR_DESIGNER>`

---

## Disclaimer

StrexoPlayer is independent and is not endorsed by Trakt, Simkl, AniList, Stremio, IntroDB, TheIntroDB, or AniSkip.

StrexoPlayer does not provide, host, sell, or distribute media content. It is a media player and API-integrated watch experience that works with the sources and services you choose to connect.

---

## Roadmap

- Improved playback reliability across more stream types
- Better Dolby Vision handling and fallback behavior
- Continued TV and mobile UI improvements
- Expanded tracking accuracy and safer matching
- More reliable skip detection across available data sources

---

Built and maintained by Callum.  
https://github.com/sponsors/CallumJRobertson
