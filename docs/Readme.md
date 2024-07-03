<div align='center'>
<a href='https://github.com/Mr-MKZ/Freecord' title="Freecord's GitHub Repository">
  <picture>
    <source srcset='https://raw.githubusercontent.com/Mr-MKZ/Freecord/master/sources/assets/icons/app.png'>
    <img src='../sources/assets/icons/app.png' height='192' alt="Freecord Logo">
  </picture>
</a>

<!-- BEGIN Readable part of the Readme file. -->

# Freecord

<!-- [![CodeQL][codeql-badge]][codeql-url] [![Build][build-badge]][build-url] -->
[![GitHub downloads][dlbadge]][downloads]
[![Discord server][discord-badge]][discord-url]

A Discord and [Spacebar] client implemented directly without [Discord API][discordapi].
Made in Iran with the [Electron][electron] framework.

</div>

## Philosophy / key features

Nowadays, Freecord is quite complex project; it can be summarized as a pack of
security and privacy hardenings, Discord features reimplementations, Electron /
Chromium / Discord bugs workarounds, stylesheets, internal pages and wrapped
<https://discord.com> page, designed to conform with ToS as much as it is
possible (or hide the changes that might violate it from Discord's eyes). For
all features, take a look at [Features.md](Features.md).

 - 🕵️ **Hardened for privacy**

Freecord does a lot to improve the privacy of the users. It blocks known tracing
and fingerprinting methods, but it does not end on it. It also manages the
permissions to sensitive APIs like camera or microphone, sets its own user agent
to the one present in Chromium browsers and spoof web API modifications in order
to prevent distinguishing it from the real Chrome/Chromium browsers.

 - 🛡️ **Using with proxy**

You can use proxies in Freecord, This feature is still under constructing but it will complete very soon.

Temporary you can just connect to Freecord using default socks and http proxies of v2rayN and you are not able to change them [**Temporary**]. 

(socks -> 127.0.0.1:10808, http -> 127.0.0.1:10809)

[dlbadge]: https://img.shields.io/github/downloads/Mr-MKZ/Freecord/total.svg?label=Downloads&color=%236586B3
[downloads]: https://github.com/Mr-MKZ/Freecord/releases "Releases"
[build-badge]: https://img.shields.io/github/actions/workflow/status/Mr-MKZ/Freecord/build.yml?label=Build&logo=github&branch=master&event=push
[build-url]: https://github.com/Mr-MKZ/Freecord/actions/workflows/build.yml "Build state"
[l10nbadge]: https://hosted.weblate.org/widgets/Freecord/-/svg-badge.svg
[l10n]: https://hosted.weblate.org/engage/Freecord/ "Help at Freecord's localization"
[Sentry]: https://sentry.io "Application Monitoring and Error Tracking Software"
[Discord-Electron]: https://github.com/GyozaGuy/Discord-Electron "An Electron Discord app designed for use on Linux systems."
[electron]: https://www.electronjs.org/ "Build cross-platform desktop apps with JavaScript, HTML, and CSS."
[electron-forge]: https://www.electronforge.io/ "A complete tool for creating, publishing, and installing modern Electron applications."
[license]: ../LICENSE "Freecord license"
[Spacebar]: https://spacebar.chat "Free, open source and selfhostable Discord compatible chat, voice and video platform."
[discordapi]: https://discord.com/developers/docs/reference "Official Discord REST API documentation"
[chromiumbounty]: https://bughunters.google.com/about/rules/5745167867576320/chrome-vulnerability-reward-program-rules "Chrome Vulnerability Reward Program Rules"
[Electron#Security]: https://www.electronjs.org/docs/latest/tutorial/security "Security | Electron Documentation"
[codeql-badge]: https://img.shields.io/github/actions/workflow/status/Mr-MKZ/Freecord/codeql-analysis.yml?label=Analysis&logo=github&logoColor=white&branch=master&event=push
[codeql-url]: https://github.com/Mr-MKZ/Freecord/actions/workflows/codeql-analysis.yml "CodeQL Analysis status"
[discord-badge]: https://img.shields.io/discord/972965161721811026?color=%2349a4d3&label=Support&logo=discord&logoColor=white
[discord-url]: https://discord.com/invite/8RjX9sKMsy "Official support server on Discord!"
