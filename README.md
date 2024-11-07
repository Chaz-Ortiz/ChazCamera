# ChazCamera

An Android camera application built with Jetpack Compose and CameraX, supporting photo and video capture with an easy-to-use UI.

## Features

- **Photo Capture**: Take high-quality photos using the CameraX library.
- **Video Recording**: Record videos with audio support.
- **Front and Back Camera Toggle**: Switch between front and back cameras with a single button tap.
- **Gallery Preview**: Easily access a gallery of recent photos through a bottom sheet interface.
- **Material Design UI**: Utilizes Jetpack Compose for a modern, Material3-styled interface.

## Screenshots

<!-- Add screenshots of your app here, e.g., home screen, photo capture, video recording, gallery preview -->

## Getting Started

### Prerequisites

Ensure you have the following permissions set up in `AndroidManifest.xml`:

```xml
<uses-permission android:name="android.permission.CAMERA" />
<uses-permission android:name="android.permission.RECORD_AUDIO" />
