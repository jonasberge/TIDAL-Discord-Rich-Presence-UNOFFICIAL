[![Discord invitation](https://img.shields.io/discord/1224509771068211292?logo=discord&logoColor=eee&label=Discord&labelColor=464ce5&color=fff)](https://discord-invite.musicpresence.app)
[![Number of downloads](https://img.shields.io/github/downloads/jonasberge/discord-music-presence/total?style=flat)](https://github.com/jonasberge/discord-music-presence/releases)
[![Donate](https://img.shields.io/badge/Donate-30363D?style=flat&logo=GitHub-Sponsors)](./FUNDING.md)

# Music Presence for Discord

![Screenshot of the application in the tray menu and the Discord status](
  ./assets/banner.png)

Music Presence allows you to show your friends what you are listening to,
no matter which media player or streaming service you are using.
It works by observing which media players are playing music on your device
and showing the information as a Discord activity.

The most notable features include:

- Fine-grained control over which applications are shared
  in your Discord status.
- Supports numerous music players and streaming services
  (support for more is being worked on!)
- The tray icon changes and reflects whether your status is currently active or not!
- Shows the streaming service or media player you are using in your status.
- Shows a button in the status that allows others to open a link the song
  (only for TIDAL right now).
- Shows the exact playback position, if the media player supports it.
- Controls are easily accessible via the tray menu.

## Supported media players

Currently, the following media players will be detected
and shared in your Discord status:

**`TIDAL`**
**`Qobuz`**
**`foobar2000`**
**`Spotify`**
**`Amazon Music`**
&nbsp;*and more...*

<span><a href="https://tidal.com"><img title="TIDAL" alt="" height="48" src="https://live.musicpresence.app/v1/tidal.ico"></a></span>&nbsp;
<span><a href="https://www.qobuz.com"><img title="Qobuz" alt="" height="48" src="https://live.musicpresence.app/v1/qobuz.ico"></a></span>&nbsp;
<span><a href="https://www.foobar2000.org"><img title="foobar2000" alt="" height="48" src="https://live.musicpresence.app/v1/foobar2000.ico"></a></span>&nbsp;
<span><a href="https://spotify.com"><img title="Spotify" alt="" height="48" src="https://live.musicpresence.app/v1/spotify.ico"></a></span>&nbsp;
<span><a href="https://www.amazon.de/dp/B00CTTEKJW"><img title="Amazon Music" alt="" height="48" src="https://live.musicpresence.app/v1/amazon-music.ico"></a></span>&nbsp;

If your media player is not listed, please
[suggest it](#my-media-player-is-not-detected),
as described below!

## Download

For downloads visit the
**[Releases](https://github.com/jonasberge/discord-music-presence/releases)**
page.
You can currently download Music Presence for **Windows**.
Support for **Mac** and **Linux** is underway
and will be added in a future update!

## Join the Discord server

Feel free to join the Discord server to stay in touch!

- **[Open the invite](https://discord-invite.musicpresence.app)**

## Donations

The development of this project largely depends
on the effort of a single developer,
who is working on this application in his free-time.
If you would like to support the development progress
or would simply like to show your appreciation,
you can do so by making a donation.
Thank you!

- **[GitHub Sponsors](https://github.com/sponsors/jonasberge)**
- **[LiberaPay](https://liberapay.com/jonasvandenberg)**
- **[PayPal](https://www.paypal.com/donate/?hosted_button_id=WJE4KJ45EZQUN)**

For more information, read [FUNDING.md](./FUNDING.md).

## My media player is not detected

> The application is still in early development.
> If your media player is not detected, simply follow the steps outlined here
> to request support for your media player or streaming service.

To report that a media player is not detected:

1. In the tray menu, navigate to "Help"
   and click on "My media player is not detected".
2. A new GitHub issue will open in your browser.
3. Please describe which media player is not detected and submit the form.

The issue will be filled out with some information about your system.
This will help me add support for the media player that you are requesting.
Once you have submitted the issue, I will come back to you as soon as I can!

## Media player support table

Overview of supported media players for each operating system.
This is still incomplete,
as Music Presence is not yet released for Mac and Linux.
This will be updated with every new version of Music Presence.

| Player | Windows | Mac | Linux |
|-|:-:|:-:|:-:|
| TIDAL | :white_check_mark: | ... | ... |
| Qobuz | :white_check_mark: | ... | :x: |
| Spotify | :white_check_mark: | ... | ... |
| foobar2000 | :white_check_mark: | ... | :x: |
| Amazon Music | :white_check_mark: | ... | :x: |

### Legend

:white_check_mark: means the player is fully supported.  
:x: means there is no desktop application for this operating system.  
&nbsp;...&ensp; means support is being worked on.

---

## Privacy

For detailed information on which data Music Presence collects
and to which services the data is sent,
please read [`PRIVACY.md`](./PRIVACY.md)
or click on "Privacy Notice" in the "Help" menu of the application.

## Roadmap

For an overview of features that are being worked on,
please read [ROADMAP.md](./ROADMAP.md).

## Changelog

For information about changes with each version
read the [CHANGELOG.md](./CHANGELOG.md) file.

## License

This project is licensed under the Music Presence license.  
For more information read the [LICENSE.txt](./LICENSE.txt) file.

## Legacy source code

For the source code of versions prior to version 2.0.0,
please visit the repository for the
[legacy source code](https://github.com/jonasberge/tidal-discord-presence).

## Disclaimer

- This software is **not** affiliated with or endorsed by Discord.  
- This software is **not** affiliated with or endorsed by
  any streaming service, media player or company that distributes music,
  including but not limited to those mentioned above.
