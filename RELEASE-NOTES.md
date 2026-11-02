# AAA IPTV release notes

## Windows x64 — 1.2.2

[Release and downloads](https://github.com/aaa-software-studio/aaa-iptv-showcase/releases/tag/windows-v1.2.2)

- Setup installer and Portable launcher are available. Both executables are unsigned.
- Settings includes Playback, Subtitles, Appearance, Storage and About.
- Saved reconnect, hardware decoding, volume and resume preferences; subtitle styling and delay; theme/text scaling and reduced motion; cache management and reset confirmation.
- Source-built mpv is retained. The build report documents replacement of WinShell operations with Windows facilities.
- Portable does not use a separate application data profile by default.
- Five assets include Setup, Portable, checksums, third-party sources and notices/licenses. First-party AAA source remains private. No Trial is included.
- Successful Setup and Portable Windows use was reported by the tester. This is not exhaustive Windows or security certification. Source/codec/device compatibility varies. Online subtitle downloads and the uosc updater remain disabled.

### Public download verification — 2026-11-02

All five Windows assets and all three Android release assets were downloaded from their public GitHub release URLs without account credentials. Their byte sizes and SHA-256 digests matched GitHub release metadata; downloaded checksum manifests also matched the covered files. Both Windows ZIP archives passed CRC checks. This verifies download integrity, not application security or native execution.

The Microsoft SDK redistribution/publisher decision remains documented as unresolved in the Windows release and accompanying notices. No new license acceptance or legal clearance is asserted by this document.

### Help

[Persian quick start and downloads](README.md) · [Report a bug or request a feature](https://github.com/aaa-software-studio/aaa-iptv-showcase/issues/new/choose)

Do not post credentials, provider/playlist URLs, tokens or unredacted screenshots/logs in public issues.

---

## AAA IPTV 2.15.0 — Android and Android TV

One signed APK for Android phones and Android TV. Build 80; application ID `com.triplea.a3stream`.

Import your own authorized media source, browse its live TV/movie/series catalogue, search and manage favorites and viewing history. No channels, subscription or content service is included.

Requires Android 6.0 or later. Source, codec and device compatibility vary. For an existing compatible installation, choose Update rather than uninstalling. The creator reports successful operation on phone and TV; this is not exhaustive device coverage or a Play Protect certification.

Download `AAA-IPTV-2.15.0-Android-TV.apk`. The notices and checksum accompany it. Windows downloads are not part of this release.

SHA-256: `c4819b05ce82e6acad228612a5f8408574d171c7d308d6934bf90f87d5800f21`
