# CULL downloads

The installers for [CULL](https://cull.photography), culling for RAW shoots, and the manifest the installed app updates itself from. The app's source is private; this repository carries only what the download page and the updater need.

**[How to install](https://cull.photography/install.html)** · [What's new](https://cull.photography/changelog.html) · [Support](https://cull.photography/support.html)

Each release carries:

- `CULL-setup.exe` and `CULL.dmg`: the Windows and Mac (Apple silicon) installers under their fixed names, so a link to them holds across versions
- `CULL_<version>_x64-setup.exe` and `CULL_<version>_aarch64.dmg`: the same two files under their versioned names
- `SHA256SUMS.txt`: the checksums, with a VirusTotal report linked per file in the release notes
- `latest.json`, `.sig` and `.app.tar.gz`: what the updater reads

The installers are not code-signed; the install page says what the first launch shows on each system and how to check a download by its checksum. Only the newest release is kept here.
