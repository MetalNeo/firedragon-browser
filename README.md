# FireDragon settings

I encourage users to find **their own setup** and to use our default configuration as something to build on top of using:
-> `~/.firedragon/firedragon.overrides.cfg`

This repository benefits from the knowledge and research provided by [arkenfox](https://github.com/arkenfox), their documentation was vital to this revamp, so special thanks to their project.
We do not use arkenfox's user.js but we try to keep up with it, and we also consider it a great resource for users who want to find their own setup.

Some of the older prefs in this project are taken from [pyllyukko](https://github.com/pyllyukko/user.js/) and many more were investigated on [bugzilla](https://bugzilla.mozilla.org/home).

Differences from LibreWolf:

- Enhanced KDE integration due to OpenSUSE patches (also using kfiredragonhelper)
- Gentoo patches for using more system libraries
- Compatible with Wayland, set MOZ_ENABLE_WAYLAND=1 as variable to enable using it
- [Searx](https://searx.garudalinux.org/) & [Whoogle](https://search.garudalinux.org/) search engines added, with the possibility to run locally with fitting optdepends installed
- The default search engine is Garudas [searX instance](https://searx.garudalinux.org)
- [Dark Reader](https://addons.mozilla.org/en-US/firefox/addon/darkreader/) & [ClearURLs](https://addons.mozilla.org/de/firefox/addon/clearurls/) added
- Sweet theme added
- Custom, dr460nized branding :dragon:
- Will keep in sync with Librewolfs changes
- Firefox accounts enabled using a custom selfhosted syncserver (ffsync.garudalinux.org)
- Presets for both profile-sync-daemon (which Garuda Linux ships by default) & Firejail available
- Builds available at [Chaotic-AUR](https://chaotic.cx)
- Icons & artwork by [SGS](https://gitlab.com/SGSm) & [zoeronen](https://gitlab.com/zoeronen)
- Tabliss setup from the screenshot can be imported from tabliss.json (needs Tabliss addon installed)
- To retain appmenu functionalities copy the firejail-fix.hook from this repo to /usr/share/libalpm/hooks/ (disabled by default)

Differences of the Nightly build:

- Built off Firefox Nightly instead of stable
- No patches available for Nightly means no KDE integration & appmenu support
- Will keep in sync with both Librewolfs & [vnepogodins](https://aur.archlinux.org/account/vnepogodin) changes

Builds for Arch based distros available at [Chaotic-AUR](https://aur.chaotic.cx).

<img src="https://gitlab.com/dr460nf1r3/dragonwolf-settings/-/raw/master/home.png/" alt="FireDragon Screenshot">
<img src="https://gitlab.com/dr460nf1r3/dragonwolf-settings/-/raw/master/about.png/" alt="About FireDragon" >


Credits go to Mozilla, Arch Linux, and:

- The [Librewolf](https://librewolf-community.gitlab.io/) project
- torvic9 & his retired [Plasmafox](https://github.com/torvic9/plasmafox)
- [vnepogodin](https://aur.archlinux.org/account/vnepogodin)
- [SGS](https://gitlab.com/SGSm) & [zoeronen](https://gitlab.com/zoeronen)
