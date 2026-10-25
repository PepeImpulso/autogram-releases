# Autogram Releases

Release binaries for Autogram — hands-free Telegram voice messages for Android Auto. The source code is open (GPL-3.0) at [PepeImpulso/autogram](https://github.com/PepeImpulso/autogram).

Download the latest APK from the [Releases](https://github.com/PepeImpulso/autogram-releases/releases) tab. Once installed, Autogram updates itself from this repo; there is no Play Store version.

Every APK is signed with the Autogram release key. You can check a download with `apksigner verify --print-certs autogram-<version>.apk`; the certificate SHA-256 must be:

```
e97d2c4cfd035043aeecf05b7ae947d41bc2f47c4d6bbaa59957484655b42699
```

Each release asset also shows its SHA-256 on GitHub, and the in-app updater checks both the signature and the hash before installing.
