# Hi, I'm Arda 👋

I build practical apps, creative tools, and personal cloud systems. My work spans the Apple ecosystem, cross-platform cloud development, self-hosting, and hardware experiments.

I develop these projects with help from **Codex**, iterating on source code, interfaces, builds, testing, and documentation.

## My projects at a glance

| Project | Focus | Current stage |
| --- | --- | --- |
| 🌙 Lunoud | Private development project | Private repository |
| 🔄 Convert | On-device file conversion for macOS and iPhone | Trial versions available |
| 🎬 Kadrena | Video editing for macOS, iPhone, and iPad | Development builds |
| 🎨 LumaStudio | Layer-based image editing for macOS | Development builds |
| 🎵 WAMP | Winamp-inspired local music player | macOS build and web version |
| ☁️ Mac mini Personal Cloud | Self-hosted storage and remote file access | Public setup guide and scripts |
| 📱 Galaxy C5 ROM | Android 9 / LineageOS 16 build | Build in progress; no phone validation |
| 💾 External macOS & NVMe research | Storage, enclosures, and Mac compatibility | Hardware research |

## 🌙 Lunoud

Lunoud is a private development project.

## 🔄 Convert — offline file conversion

[Convert](https://github.com/ardacob/convert-offline) is a **macOS and iPhone** file converter built with **Swift and SwiftUI**. Conversion happens on the device, without uploading files to a conversion server.

### Features

- File selection, suggested target formats, previews, and saving/sharing results.
- Image and PDF conversion.
- Selected audio/video conversions using the operating system's supported frameworks and codecs.
- Batch image conversion on iPhone from Photos or Files, including **HEIC → JPG**.
- Sharing multiple converted images together.
- Light, dark, and Liquid Glass themes, with adjustable transparency.
- A separate settings screen for theme preferences and app information.

### Current status

Trial versions and source code are available for macOS and iPhone. The original wider platform idea has evolved into native Apple applications.

Format coverage depends on the input and system codecs. MP3 output, many office/specialized formats, and Windows/Android applications are not included in the current published version.

[Source code](https://github.com/ardacob/convert-offline) · [Releases](https://github.com/ardacob/convert-offline/releases) · [Format scope](https://github.com/ardacob/convert-offline/blob/main/FORMAT_SCOPE.md)

## 🎬 [Kadrena](https://github.com/ardacob/kadrena) — video editing

**Kadrena** is my video editing project for **macOS, iPhone, and iPad**, inspired by approachable timeline-based editors such as CapCut and Clipchamp.

The goal is to make everyday editing straightforward: bring in local video and audio, arrange clips, cut them, add music, and export the result.

### Features developed

- Video and audio import from local files.
- Timeline editing, clip movement, trimming, and splitting.
- Music/audio tracks and fade controls.
- Aspect-ratio selection.
- Full-screen previews.
- Project saving.
- **MP4, MOV, and M4V** export.
- A touch-oriented timeline for iPhone and iPad.

### Current status

macOS and mobile development builds have been prepared. The iPhone version was installed and launched on a physical device.

Broader format support remains a development goal; the current project does not promise export to every video format.

## 🎨 [LumaStudio](https://github.com/ardacob/lumastudio) — layer-based image editing

**LumaStudio** is my **macOS** image editor, inspired by Photoshop's layered workflow and a soft, Apple-style interface.

### Features developed

- Creating a blank canvas.
- Adding image, text, shape, and brush layers.
- Moving, reordering, hiding, duplicating, and deleting layers.
- Adjusting layer opacity.
- Saving and reopening editable **`.luma` projects**.
- Exporting the combined image.
- System, light, and dark appearance settings.
- Persistent default export format and quality preferences.

### Current status

Development builds have been prepared for **Apple Silicon and Intel Macs**. Layer save/reopen and combined-image export were verified during development.

Full Photoshop compatibility is still outside the current feature set. Masks, advanced selection tools, and layered PSD interchange remain future work; current PSD export produces a flattened image.

## 🎵 [WAMP](https://github.com/ardacob/wamp) — classic music player

**WAMP** is my **Winamp-inspired music player**, with both a macOS application and a browser version.

### Features developed

- A classic dark metallic interface and green display.
- A playlist and familiar playback controls.
- Local audio file selection.
- Drag-and-drop files into the web playlist.
- Playback without uploading personal audio files to a server.
- An offline HTML version alongside the web application.

### Current status

The macOS build was prepared for **Apple Silicon and Intel Macs**, and file selection/playback were tested on macOS. A web version is also available.

[Open the web player](https://wamp-klasik-mp3-calar.sykenix.chatgpt.site)

## ☁️ Mac mini Personal Cloud — self-hosted storage

[Mac mini Personal Cloud](https://github.com/ardacob/mac-mini-personal-cloud) documents a real personal cloud and media-storage setup using:

**Apple Silicon Mac mini + external NVMe SSD + Docker + File Browser + Tailscale + NAStool**

### What the project covers

- Remote file access and uploads from iPhone/iPad.
- Tailscale access without opening router ports to the public internet.
- Sharing one physical SSD between file management and media services.
- Diagnosing macOS NTFS read-only behavior and moving to APFS.
- Investigating black, partial, or incorrect HEIC previews.
- Comparing FFmpeg and macOS `sips` conversion results.
- Preview/cache troubleshooting.
- A DOM-based Turkish interface approach for NAStool.
- Backup, rollback, and troubleshooting documentation.

### Practical deliverables

The repository includes Docker configuration examples, setup guides, and helper scripts for storage diagnosis, folder creation, HEIC preview refresh, backups, and stack verification.

NAStool is an archived upstream project, so the guide records it as a legacy component.

[Repository & Turkish guide](https://github.com/ardacob/mac-mini-personal-cloud) · [English guide](https://github.com/ardacob/mac-mini-personal-cloud/blob/main/README_EN.md)

## 📱 Galaxy C5 — custom Android ROM work

I'm working on an **Android 9 / LineageOS 16** build for the **Samsung Galaxy C5 SM-C5000**.

### Work carried out

- Preparing an Ubuntu-based Android build environment.
- Downloading and pinning the LineageOS, device, kernel, and vendor sources.
- Resolving older Android build-tool compatibility issues.
- Fixing a device-tree compiler symbol conflict.
- Correcting recovery image address arguments.
- Building a recovery image and checking its size, headers, and address layout.
- Preparing a stock firmware return package and shared-storage backup.
- Preparing a transfer of the Linux build environment to a Windows laptop.

### Current status

The recovery passed build-level checks, but it has **not been tested on the phone**. The full ROM build is still in progress, and bootloader/firmware compatibility remains unresolved.

The phone has not been flashed with the custom recovery or ROM. Build validation is not a claim of successful device boot.

## 💾 External macOS & NVMe — hardware research

Alongside the apps, I research practical storage setups for the **Mac mini**, including a **Crucial T500 NVMe SSD**, external enclosures, and possible external macOS boot use.

### Topics explored

- USB 3.1 Gen 2 versus USB4/Thunderbolt enclosure options.
- NVMe size and interface compatibility.
- APFS formatting and storage organization.
- Enclosure cooling and price/performance comparisons.
- Sleep/wake behavior and the distinction between file-storage compatibility and reliable macOS boot use.

### Current status

This is a hardware research track. A particular enclosure's compatibility on paper is not treated as proof of a stable external macOS installation.

## Technologies & interests

- 🍎 **Apple apps:** Swift, SwiftUI, macOS, iOS, Apple Silicon
- ☁️ **Cloud & self-hosting:** Docker, Docker Compose, File Browser, Tailscale, remote-access architecture
- 🎞️ **Files & media:** HEIC, PDF, FFmpeg, image layers, audio playback, video timelines
- 🐧 **Systems:** Linux build environments, Android/LineageOS, recovery images
- 🔧 **Hardware:** NVMe storage, APFS, homelab, troubleshooting

## How I work

I use **Codex** as a development collaborator for source changes, interface iteration, build troubleshooting, verification, and project documentation.

My aim is to turn everyday needs into useful tools, keep project status honest, and record the practical lessons along the way.

Public repositories and demos are linked where available. Other projects are still being developed and packaged.

