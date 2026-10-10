# PokeChampSim — Android APK Downloads

This public repository holds **signed Android APK release artifacts only**.
The source code and original Android signing key remain private.

- [Latest release](https://github.com/MasayukiKimura/PokeChampSim-Downloads/releases/latest)
- [Latest signed APK](https://github.com/MasayukiKimura/PokeChampSim-Downloads/releases/latest/download/PokeChampSim.apk)
- [SHA-256 file](https://github.com/MasayukiKimura/PokeChampSim-Downloads/releases/latest/download/PokeChampSim.apk.sha256)

Links become active **after** the first verified public release.

APK files are built by Codemagic's macOS runner, signed with the **same permanent Android certificate** as the previously distributed application, and checked before publication. Existing application updates must keep the original signature and use a greater Android versionCode.

The public repository must never contain an Android keystore, passwords, access tokens, decrypted keys, or private application source code.
