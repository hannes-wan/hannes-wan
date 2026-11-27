# Hannes Software

Desktop software for people who need to understand a system, shape an artifact, practise a difficult passage, or run a clinic without sending the work through a generic web service.

Hannes Software builds focused **Windows and Linux** workbenches around observable evidence: packets and captures, musical timing and pitch, and clinic records. The engineering thread is consistent—keep sensitive inputs on the desktop, make automated decisions reviewable, and produce artifacts that a human can inspect.

**All Community Editions are free.** Start from [hannes-software.com](https://hannes-software.com/), watch real `-14 LUFS` audio & workflow walkthroughs on [YouTube (@HannesSoftware)](https://www.youtube.com/@HannesSoftware), or install directly from our official Windows Scoop bucket.

## Quick install on Windows (Scoop)

```powershell
scoop bucket add hannes-software https://github.com/hannes-wan/scoop-hannes-software
scoop install hannes-software/thump-forge hannes-software/tone-forge hannes-software/jamloom
```

Browse all 15 manifests in [scoop-hannes-software](https://github.com/hannes-wan/scoop-hannes-software). Native Linux packages (`.AppImage`, `.deb`, `.rpm`) and Windows setup installers are published on every product's GitHub Releases page and on [hannes-software.com/music-tools/](https://hannes-software.com/music-tools/).

## Music analysis, synthesis, and practice systems

| Product | Engineering core | Official links |
| --- | --- | --- |
| **Thump Forge** | Dedicated electric bass amp simulator, 12-module effects rack, chromatic 5-string tuner, and Windows VST3 plugin built for low-latency live practice, tracking, and re-amping. | [Product](https://hannes-software.com/thump-forge/) · [Watch Demo](https://hannes-software.com/watch/thump-forge/) · [Releases](https://github.com/hannes-wan/thump-forge-official) |
| **Tone Forge** | Virtual modular synthesizer and Windows VST3 instrument with an explicit oscillator, filter, envelope, and stereo effects graph for live MIDI play and sound design. | [Product](https://hannes-software.com/tone-forge/) · [Watch Demo](https://hannes-software.com/watch/tone-forge/) · [Releases](https://github.com/hannes-wan/tone-forge-official) |
| **JamLoom** | Offline backing-track and chord-chart rehearsal studio with 648 built-in practice charts, real-time bass/drum/guitar accompaniment, independent part mixing, and Type-1 MIDI, WAV, and PDF export. | [Product](https://hannes-software.com/jamloom/) · [Watch Demo](https://hannes-software.com/watch/jamloom/) · [Releases](https://github.com/hannes-wan/jamloom-official) |
| **Score Craft** | Offline sheet music scanner (OMR) and score proofreading studio that turns printed PDFs and photos into editable grand-staff notation with cropped source previews, Salamander Grand playback, and MusicXML/MIDI/WAV export. | [Product](https://hannes-software.com/score-craft/) · [Watch Demo](https://hannes-software.com/watch/score-craft/) · [Releases](https://github.com/hannes-wan/score-craft-official) |
| **Melody Craft** | Offline audio-to-MIDI transcription workbench for single vocal or instrument takes, preserving stepped pitch-bend curves, loudness-matched A/B auditioning, and piano-roll editing. | [Product](https://hannes-software.com/melody-craft/) · [Watch Demo](https://hannes-software.com/watch/melody-craft/) · [Releases](https://github.com/hannes-wan/melody-craft-official) |
| **Fretboard Lab** | Guitar chord chart maker that parses real symbols, generates voicings under physical fretboard constraints, and ranks candidates by position, span, difficulty, and open-string use. | [Product](https://hannes-software.com/fretboard-lab/) · [Watch Demo](https://hannes-software.com/watch/fretboard-lab/) · [Releases](https://github.com/hannes-wan/fretboard-lab-official) |
| **Type Piano** | Complete free virtual piano whose computer-keyboard, native MIDI, and on-screen 88-key inputs share one performance state, realtime synth, and source-attested streamed grand-piano bank. | [Product](https://hannes-software.com/type-piano/) · [Releases](https://github.com/hannes-wan/type-piano-official) |
| **Backbeat Forge** | Audio-to-MIDI drums and percussion notation moving from local separation and hit evidence into editable five-line scores, two-voice percussion semantics, and General MIDI channel 10 export. | [Product](https://hannes-software.com/backbeat-forge/) · [Releases](https://github.com/hannes-wan/backbeat-forge-official) |
| **LowEnd Forge** | Bass tab generator fusing Basic Pitch onset evidence with CREPE monophonic pitch tracking, keeping octave correction, note boundaries, and four-string tablature open to musical review. | [Product](https://hannes-software.com/lowend-forge/) · [Releases](https://github.com/hannes-wan/lowend-forge-official) |
| **Practice Rack** | Standalone guitar amp sim and practice rack with an ordered real-time DSP chain, nonlinear drive stages, cabinet IR convolution, modulation, delay, reverb, FFT tuning, looping, and WAV capture. | [Product](https://hannes-software.com/practice-rack/) · [Releases](https://github.com/hannes-wan/practice-rack-official) |
| **Session Craft** | Local music practice app combining HTDemucs stem separation with phase-vocoder time stretching, transposition, aligned loops, and session state for rehearsal without a cloud round trip. | [Product](https://hannes-software.com/session-craft/) · [Releases](https://github.com/hannes-wan/session-craft-official) |

The model output is never treated as an oracle. Timing, confidence, pitches, kit pieces, voicings, loops, and notation remain visible enough to correct—because useful music software must respect the performance, not merely emit a file.

## Protocol diagnostics and capture engineering

| Product | Engineering core | Official links |
| --- | --- | --- |
| **RTSP Inspector** | An RTSP stream tester that reconciles RTSP transactions and SDP with RTP continuity and RTCP timing, turning camera failures into a reviewable control-plane and media-plane evidence trail. | [Product](https://hannes-software.com/rtsp-inspector/) · [Releases](https://github.com/hannes-wan/rtsp-inspector-official) |
| **Bus Scope** | A free USB analyzer that connects Linux `usbmon` and Windows USBPcap capture readiness to filtered transfer timelines, setup packets, descriptors, endpoint state, and raw payload evidence. | [Product](https://hannes-software.com/bus-scope/) · [Releases](https://github.com/hannes-wan/bus-scope-official) |
| **PCAP Surgery** | A PCAP analyzer and editor that previews bounded header rewrites, identifies supported IPv4/TCP/UDP checksum repairs, and keeps packet scope, privacy evidence, and the untouched source visible before export. | [Product](https://hannes-software.com/pcap-surgery/) · [Releases](https://github.com/hannes-wan/pcap-surgery-official) |

These are not generic packet viewers. They are evidence workbenches: the selected transaction, transfer, packet, byte range, warning, and derived artifact remain connected so a diagnosis can survive handoff.

## Local clinic operations

| Product | Engineering core | Official links |
| --- | --- | --- |
| **Dental Ark** | A dental clinic management software workflow that keeps patient, appointment, visit, billing, and image records in local SQLite, with native FDI charting, explicit clinical states, and restorable manifest-backed backups. | [Product](https://hannes-software.com/dental-ark/) · [Releases](https://github.com/hannes-wan/dental-ark-official) |

## Channels & public repositories

- **Website & Demos**: [hannes-software.com](https://hannes-software.com/) · [Music Tools](https://hannes-software.com/music-tools/)
- **YouTube**: [@HannesSoftware](https://www.youtube.com/@HannesSoftware) (loudness-matched `-14 LUFS` audio demos & walkthroughs)
- **Windows Scoop Bucket**: [hannes-wan/scoop-hannes-software](https://github.com/hannes-wan/scoop-hannes-software)
- **Engineering Notes**: [DEV.to (@hannes_wan)](https://dev.to/hannes_wan) · [Bluesky (@hannes-software.com)](https://bsky.app/profile/hannes-software.com)

These public repositories are **proprietary product distribution and community repositories**, not source-code releases. They provide verified desktop releases and SHA-256 checksums, product documentation, and structured bug/feature intake.
