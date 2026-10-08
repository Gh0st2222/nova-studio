# Nova Studio

**Nova Studio is where you make experiences for [Nova](https://nova-woad-phi.vercel.app).** Build worlds with parts, script them in GDScript, test them with several players on your own computer, and publish them to Nova with one button. Players find them on the website and play them with Nova Player.

## Download

**[Download Nova Studio for Windows](https://github.com/Gh0st2222/nova-studio/releases/latest/download/NovaStudio.exe)** (the latest release, always), or get it from the [Download page](https://nova-woad-phi.vercel.app/download) on the Nova website.

Run `NovaStudio.exe`. It installs itself for your Windows account (in `%LOCALAPPDATA%\Nova Studio`, with a **Nova Studio** shortcut in the Start menu) and opens. No administrator rights needed.

> Windows may say "Windows protected your PC", because Nova Studio isn't code-signed yet. Choose **More info**, then **Run anyway**.

## Learn

The **[Dev Bible](https://nova-woad-phi.vercel.app/docs)** is the guide to making experiences: your first experience, building, scripting, multiplayer, four step-by-step tutorials (every one tested by playing it), publishing, and the full API reference.

## Updates

Nova Studio keeps itself up to date. When it starts, it checks for a newer release here and downloads it in the background; when it's ready, you can restart right away, or it switches the next time you open Nova Studio. Every download is checked (SHA-256) before it's used. The files it needs beside it (NVIDIA's DLSS libraries) come with each release the same way, and are put back if they go missing.

Each release has a `latest.json` that says what the newest version is and where to get it.

## Requirements

Windows 10 or 11, 64-bit, with a graphics card that supports Vulkan or Direct3D 12 (Nova Studio uses the Forward+ renderer). 8 GB of memory or more. To try NVIDIA DLSS in your experiences: an NVIDIA GeForce RTX card (Frame Generation: RTX 40 series or newer).

**Uninstall:** delete `%LOCALAPPDATA%\Nova Studio` and the Nova Studio shortcut in the Start menu. Your experiences stay wherever you saved them.

## Licenses

Nova Studio is free to download and use. Its source code isn't public.

Nova Studio is built on [Godot Engine](https://godotengine.org), which is open source under the MIT license. The notices for Godot and the libraries it includes are in [GODOT_LICENSE.txt](GODOT_LICENSE.txt) and [THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt).

NVIDIA DLSS: Nova Studio includes NVIDIA's DLSS libraries (`nvngx_dlss.dll` and `nvngx_dlssg.dll`, © NVIDIA Corporation), which it keeps beside itself for DLSS, DLAA and DLSS Frame Generation on NVIDIA RTX graphics cards. They're NVIDIA's, under the NVIDIA RTX SDKs license (its text is in [THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt)): you may not reverse engineer, decompile, disassemble or modify them, or distribute them on their own. NVIDIA, DLSS and Reflex are trademarks of NVIDIA Corporation.
