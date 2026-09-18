# RETINA — Windows + Android Releases

**RETINA** is an offline AI-assisted diabetic retinopathy research prototype for supported color fundus image analysis.

This public repository is used **only to distribute final Windows and Android application builds**.

> The main RETINA source code, research scripts, model-development files, and technical project history remain in a separate private repository.

## Downloads

The final public release should contain:

- **Android:** `RETINA_ANDROID_FINAL.apk`
- **Windows:** `RETINA_WINDOWS_FINAL.zip`
- **Checksums:** `RETINA_FINAL_SHA256.txt`

After the release is published, the direct latest-download links are:

### Android
`https://github.com/ElnathanCoding/RETINA-Releases/releases/latest/download/RETINA_ANDROID_FINAL.apk`

### Windows
`https://github.com/ElnathanCoding/RETINA-Releases/releases/latest/download/RETINA_WINDOWS_FINAL.zip`

## Final release identities

### Android
- File: `RETINA_ANDROID_FINAL.apk`
- SHA-256: `C4DCA6AB7D7A956C6E122850FDA19A635CA8C9A3CF3647CC5AE60587B40ACCF9`

### Windows
- File: `RETINA_WINDOWS_FINAL.zip`
- SHA-256: `1B7450B5C91D6A1D99041970094510957AF7EA2F8C3DC23C65EED62B6045402E`

## Installation

### Android
1. Download `RETINA_ANDROID_FINAL.apk`.
2. Open the APK on the Android device.
3. If Android asks for permission to install from the browser/file manager, allow that source.
4. Complete installation and launch RETINA.

Because the APK is distributed outside Google Play, Android may show a sideloading/security warning.

### Windows
1. Download `RETINA_WINDOWS_FINAL.zip`.
2. Extract the entire ZIP to a folder.
3. Keep all packaged DLL/runtime files together with the executable.
4. Launch the RETINA Windows application from the extracted folder.

## Verify downloads

Windows PowerShell:

```powershell
Get-FileHash .\RETINA_ANDROID_FINAL.apk -Algorithm SHA256
Get-FileHash .\RETINA_WINDOWS_FINAL.zip -Algorithm SHA256
```

Compare the results with the SHA-256 values above.

## Research-use notice

RETINA is a **research and educational prototype**. Its AI-assisted output is **not an independent clinical diagnosis** and must not replace professional retinal examination, clinical judgment, or consultation with a qualified eye-care professional.

## Privacy and source-code access

The released applications are designed for offline inference. Public access to this repository provides the packaged applications only and does **not** provide access to the private RETINA development repository or source code.

## Redistribution

The packaged Android and Windows builds may be shared for research/educational demonstration together with the research-use notice above.

---

**Project:** RETINA — Diabetic Retinopathy AI Research Prototype
