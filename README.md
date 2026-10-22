# Pastel Paws AR 🐾

**Pastel Paws AR** is an Android augmented reality (AR) mobile application built with **Unity 6.3 LTS**, **AR Foundation** and **Google ARCore** for a university course project.

Users can detect real-world surfaces through their phone camera and place, select, rotate and remove virtual 3D objects.

## Features

- Real-world surface detection (AR plane detection)
- Place 3D objects on detected surfaces
- Select and rotate objects using touch interactions
- Remove placed objects
- Kawaii-inspired pastel pink interface and welcome screen
- Six object categories: cat, dog, donut, ice cream, chocolate and coffee cup

## Tech Stack

- Unity 6.3 LTS (6000.3.27f1)
- AR Foundation + ARCore
- Android
- Unity XR Interaction Toolkit / AR Mobile template

## Project Structure

This is a Unity project. To reopen it, launch Unity Hub and add the project folder containing `Assets/`, `Packages/`, and `ProjectSettings/`.

> The `Library/`, `Temp/`, `Logs/` and other generated Unity directories are intentionally excluded from Git.

## Running the Project

1. Install Unity Hub and **Unity 6.3 LTS** with **Android Build Support**, Android SDK & NDK Tools, and OpenJDK.
2. Open the project folder in Unity Hub.
3. Open the `PastelPawsScene` scene (under the project's Scenes folder).
4. Switch the build profile to Android and ensure Google ARCore is enabled under XR Plug-in Management.
5. Confirm the minimum API level is compatible with the Android device (tested build setting: API 30).
6. Build an APK or install the APK attached to this repository's Release, if one has been published.

The AR camera and surface placement functionality requires a compatible Android device and cannot be fully tested in Unity's ordinary desktop Game view.

## Download APK

Go to **Releases** on this GitHub repository and download `PastelPawsAR5.apk` (if attached).

## Credits and Third-Party Assets

This project uses Unity's AR Mobile template and imported models from third-party Unity Asset Store packs, including PolyOne Studio's Cartoon Dog/Cat pack and HQP Studios' Low Poly Sweets pack. See the original asset pages for the corresponding license terms.

**Important:** Imported Asset Store source assets may not be redistributed publicly under their licenses. If this repository contains third-party asset source files, keep it private and grant access only to authorized reviewers, or remove/relicense those assets before making it public.

## Notes

This project was created for educational purposes.
