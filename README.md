# RETINA — Android Releases

**RETINA** is an offline AI-assisted diabetic retinopathy research prototype for color fundus image analysis.

This public repository is used **only to distribute signed Android APK releases**.

> The main RETINA source code, research scripts, model-development files, and technical project history are maintained separately in a private repository.

## Download

The latest Android release will be available from the **Releases** section of this repository.

Once a release is published, the permanent latest-download format is:

`https://github.com/ElnathanCoding/RETINA-Releases/releases/latest/download/RETINA_ANDROID_FINAL.apk`

## Current release identity

- Application: **RETINA Research Prototype**
- Platform: **Android**
- APK filename: `RETINA_ANDROID_FINAL.apk`
- SHA-256: `C4DCA6AB7D7A956C6E122850FDA19A635CA8C9A3CF3647CC5AE60587B40ACCF9`

You can verify a downloaded APK on Windows PowerShell with:

```powershell
Get-FileHash .\RETINA_ANDROID_FINAL.apk -Algorithm SHA256
```

The resulting hash should match the SHA-256 value above.

## Installation

1. Download `RETINA_ANDROID_FINAL.apk` from the latest GitHub Release.
2. Open the APK on your Android device.
3. If Android asks for permission to install apps from your browser or file manager, allow it for that source.
4. Complete the installation.
5. Launch RETINA.

Because the application is distributed outside Google Play, Android may show a sideloading/security warning during installation.

## Research-use notice

RETINA is a **research and educational prototype**. Its AI-assisted output is **not an independent clinical diagnosis** and must not replace professional retinal examination, clinical judgment, or consultation with a qualified eye-care professional.

## Privacy

The released application is designed for offline inference. Public access to this repository does **not** expose the private RETINA development repository or its source code.

## Redistribution

The APK can be downloaded and shared for research/educational demonstration. Anyone receiving the APK should be given the same research-use notice above.

---

**Project:** RETINA — Diabetic Retinopathy AI Research Prototype
