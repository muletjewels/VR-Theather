# VR WebXR Cinema (Prototype)

A small WebXR/A-Frame prototype for watching videos in an immersive VR “cinema” style UI.
Designed to be lightweight for standalone headsets (tested in browser), and easy to run locally.

## What this is
- VR/WebXR scene with a video screen + simple controls
- Intended for quick experiments with 2D/3D playback and UI usability in VR
- Focus: fast load, readable UI, minimal dependencies

## How I test locally
I use **Caddy** to serve the project in the local network (LAN),
so I can open it from other devices (phone / headset browser).

> Note: The project may include local LAN URLs (e.g. 192.168.x.x) for video testing.
> These links work only inside the local network.

If a default video URL points to a local IP, the page will still load, but the video may not play outside LAN.

## Tech
- HTML / CSS / JavaScript
- A-Frame (WebXR)
- Optional: PeerJS (if syncing features are enabled in this version)


## License
Personal use only (non-commercial). See LICENSE file.
