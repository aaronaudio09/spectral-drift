# Spectral Drift

A Winamp-style music visualizer that turns whatever you're playing into living visuals.

**Try it in your browser:** https://aaronaudio09.github.io/spectral-drift/

**Windows app (free):** [Microsoft Store](https://apps.microsoft.com/detail/9P8FM3XZN945)

![Spectral Drift](screenshot.jpg)

## What it does

Seventeen visualizers: Hyperspace (endless zooms through space or your own picture), Sound Weaver (fly through glowing 3D ribbons the music writes as it plays), Music Box (every note the music plays draws its own line on a slowly turning drum: the notes set the lines, not the loudness), 3D Worlds (ten scenes drawn on your graphics card), Ink (a real fluid simulation you stir with the mouse), Swarm, Mandala, Laser show, 98 classic MilkDrop presets (242 with the extra pack), an AVS-style effect builder, the Classic analyzer and Reactor — plus five where the music is the mathematics:

- **Harmony Lattice** — the twelve notes laid out so that a perfect fifth is one step right and a major third one step up, which makes every small triangle a chord: up for major, down for minor. The notes playing light up, chords fill in as glowing plates, and the view drifts toward whatever key the music is in (the average of the notes around the circle of fifths).
- **Cymatics** — sand on a vibrating plate. A plate mode's pitch goes as √(n²+m²), so every note sounding is matched to the standing wave whose pitch it is: one note draws a clean Chladni figure, a chord draws the sum of them.
- **Sound Terrain** — the spectrum's own history as a landscape you fly over. Each slice becomes one ridge and stays where it was cut; by default a new slice is cut every quarter beat, so the rhythm lines the ridges up into bars.
- **Attractor** — a chaotic system (Lorenz, Rössler, Thomas, Aizawa, Halvorsen, De Jong, Clifford) whose constants *are* the bass, mids and highs, so the music chooses the shape the equations settle into; kicks and snares knock the point onto a new path.
- **Song Memory** — every moment of the track compared with every moment before it, the self-similarity picture Foote brought to music analysis. A repeated chorus draws a line parallel to the diagonal, a held section fills a block, and a checkerboard slid along the diagonal finds the edges between sections as it plays.

Bass, mid and high each drive the picture their own way, kicks, snares and hats hit harder, and Dynamics decides how calm quiet music looks. **Bright** dims or lifts every visualizer at once without changing how it reacts. Save any picture you like as a named look and bring it back later.

## Controls

The controls you reach for most are always in view: the visualizer and its scene (with Prev, Random and Next), Play with one **Source** menu (demo loop, a track, the microphone, or what your computer is playing), **Bright**, **Vol** and **Save**. Below them, **Feel** has four sliders (Reaction, Motion, Color pulse, Trails) and a **Music focus** row (Balanced, Bass, Melody, Hits), then the visualizer's own dials, key dials first with the rest one tap away. Everything else waits under **More**: the per-band drives and Dynamics, fine tuning, beat detection, **Auto-change** (off unless you turn it on) and **Render quality**.

## Your looks on every device

Saved looks stay on the device you made them on. To have them everywhere, press **Sign in with Google** under Saved looks — in the browser, in the Windows app and in the Android app — and they follow you to every device you sign in on. Signing in is optional. (A copy opened straight off the disk as a `file://` page can't sign in: Google needs a web address. Self-hosting your own copy? Add its address under Authentication → Settings → Authorized domains in the Firebase console; until you do, the sign-in button says so and names the address.) It stores your Google sign-in details (account ID, name, email address and profile picture link) and your saved looks in Google Firebase, used for nothing but syncing them. **Sign out** stops syncing; **Delete cloud copy** erases your looks and your sign-in record from it.

## On your TV

Press the cast button at the top right of the picture (or **C**) to send the visualizer to a Chromecast, an Android TV or any Google Cast device on your Wi-Fi. The TV draws the picture and follows every dial you move; the music keeps playing on the device you started from, which does the listening. Press it again to stop. It works the same from the browser, the Windows app and the Android app. In a browser without Cast support, its own **Cast…** menu still mirrors the tab.

## On a Mac

Use Chrome or Edge. Press ▶ for the built-in demo, or open **Source** to load a track or pick **Microphone**. To visualize what your Mac is playing (Spotify, YouTube…), pick **Source → System audio** and share your screen with **Share system audio** turned on; that needs Chrome 141 or newer on macOS 14.2 or newer. The video is dropped straight away; nothing is recorded or uploaded.

## Keys

Space play/pause · N / P next/previous · R random · E next visualizer · F fullscreen · H hide controls · S save the look on screen · C cast to a TV

No ads, no tracking. Made by Aaron Does It.
