# Netwright Studio updates

This repository holds the signed update feeds and installers that Netwright Studio downloads when you press
**Settings › Updates › Check for Updates**. It is served by GitHub Pages at
https://ahmedalbazzaz1987.github.io/netwright-updates/.

- `windows/appcast.xml` and the Windows installers (`Netwright-Studio-<version>-Windows-Setup.exe`)
- `mac/appcast.xml` and the Mac disk images (`Netwright-Studio-<version>.dmg`)

Every installer is signed with the publisher's Ed25519 key. The app checks the size and signature against the public
key built into it before it opens anything it downloaded, so a file changed here or on the way is refused.
