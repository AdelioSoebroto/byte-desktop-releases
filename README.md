# Whiskerly (Byte Desktop) releases

Whiskerly (called Byte Desktop in its file names) is a calico cat that lives on your Mac's desktop:
it walks along the bottom of the screen and the tops of windows, naps, grooms, chases a ball or a
butterfly, and can be petted, picked up and fed from the cat icon in the menu bar.

## The problem it solves

A Mac desktop is a quiet, solitary place to work. Whiskerly is a small companion that makes it feel
lived-in without getting in the way: it keeps off your work, rests when you do, and uses roughly
1–3% of one CPU core. You adopt a kitten, look after it, and it grows up, so there is a little story
to come back to.

## How it works

- A native Mac app (Swift, AppKit and Core Animation) that draws the cat in a transparent window over
  your desktop, in step with each screen's refresh rate, with fewer effects on battery, when warm, or in
  Low Power Mode.
- A pet has needs (food, happiness, energy, health), five coat colours, a name and life stages from
  newborn kitten to adult. How well you care for it changes how it grows. You can keep up to three pets.
- This repository only hosts the installer and the signed update files. The app updates itself from here.

## Install

1. Download **Byte-Desktop-Installer.pkg** from the [latest release](https://github.com/AdelioSoebroto/byte-desktop-releases/releases/latest).
2. Double-click it. The first time, macOS may say it cannot check the installer: click **Done**, open
   **System Settings › Privacy & Security**, and click **Open Anyway** next to the message about it.
3. Follow the installer. The cat appears straight away and starts by itself at every login.

Works on any Mac with Apple silicon (M1 or later), macOS 11 or later.

## Updates

The app updates itself: it checks here every few hours and installs a new version while the cat is
resting. Every update is signed, and the app refuses anything not signed with its release key. Turn it
off with **Update automatically** in the cat's menu, or update at once with **Check for updates…**.
