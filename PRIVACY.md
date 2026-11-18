# ZetPlayer privacy policy

Last updated: 18 November 2026

ZetPlayer is a music player made by Zetph. This policy covers the Windows
and Android apps.

## The short version

ZetPlayer has no accounts, no adverts, and no analytics or tracking. Zetph
runs no servers that the app reports to and receives nothing about you,
your music, or how you use the app. Your library, playlists, listening
history, and settings stay on your device.

The app does contact other services, but only to do something you can see
in the app, and only with the details that job needs. They are listed
below.

## What stays on your device

- Your music library index, playlists, likes, ratings, play counts,
  listening history, bookmarks, lyrics, settings, and themes.
- Passwords and access tokens for network sources and scrobbling services.
  These are kept in Windows Credential Manager or the Android Keystore,
  not in the app's own files.
- Backups you make. They hold no music and no passwords, and they go only
  where you save them.

## Services the app contacts

| Service | When | What is sent |
|---|---|---|
| LRCLIB (lrclib.net) | When lyrics are looked up online, if that is switched on or you ask for it | The song's title, artist, album, and length |
| MusicBrainz (musicbrainz.org) | When you look up album details | The album and artist names, or identifiers already in your files' tags |
| Cover Art Archive (coverartarchive.org) | When cover art is fetched for a matched album | The album's MusicBrainz identifier |
| Last.fm | Only if you connect it | Your Last.fm sign-in when you connect, then each song you play: title, artist, album, length, track number, and the time |
| ListenBrainz | Only if you connect it | Your user token, and the same song details as above |
| Discord | Only if you switch on Discord status, and Discord is running on the same computer | The playing song's title, artist, and album, passed to your own Discord app, which shows it on your profile |
| Your own servers (SMB, WebDAV, Navidrome or Subsonic, Jellyfin) | Only for sources you add | Your sign-in for that server, and requests for your music |
| GitHub (github.com) | Windows installer version only, when checking for updates | A request for the list of releases. No details about you or your library |

Every one of these services sees your internet address, as any website
does, and handles it under its own privacy policy. The Microsoft Store
version does not contact GitHub; the Store updates it.

## What Zetph receives

Nothing from the app. If you buy ZetPlayer from the Microsoft Store,
Microsoft handles the purchase and shares sales totals with Zetph, not
your payment details.

## Children

ZetPlayer is not directed at children and collects no information from
anyone.

## Changes

If this policy changes, the new version will be posted here with a new
date.

## Contact

Questions about this policy: <zetplayer.support@gmail.com>
