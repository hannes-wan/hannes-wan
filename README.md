# Hannes Software

Desktop software for people who need to understand a system, shape an artifact, practise a difficult passage, or run a clinic without sending the work through a generic web service.

Hannes Software builds focused Windows and Linux workbenches around observable evidence: packets and captures, musical timing and pitch, and clinic records. The engineering thread is consistent—keep sensitive inputs on the desktop, make automated decisions reviewable, and produce artifacts that a human can inspect.

**All Community Editions are free.** Start from an official product repository or the [Hannes Software desktop product studio](https://hannes-software.com/).

## Protocol diagnostics and capture engineering

| Product | Engineering core | Official entry |
| --- | --- | --- |
| **RTSP Inspector** | Reconciles RTSP transactions and SDP with RTP continuity and RTCP timing, turning camera-stream failures into a reviewable control-plane and media-plane evidence trail. | [Repository](https://github.com/hannes-wan/rtsp-inspector-official) · [Product](https://hannes-software.com/rtsp-inspector/) |
| **Bus Scope** | Connects Linux `usbmon` and Windows USBPcap capture readiness to filtered transfer timelines, setup packets, descriptors, endpoint state, and raw payload evidence. | [Repository](https://github.com/hannes-wan/bus-scope-official) · [Product](https://hannes-software.com/bus-scope/) |
| **PCAP Surgery** | Previews bounded header rewrites, identifies supported IPv4/TCP/UDP checksum repairs, and keeps packet scope, privacy evidence, and the untouched source visible before an optional export. | [Repository](https://github.com/hannes-wan/pcap-surgery-official) · [Product](https://hannes-software.com/pcap-surgery/) |

These are not generic packet viewers. They are evidence workbenches: the selected transaction, transfer, packet, byte range, warning, and derived artifact remain connected so a diagnosis can survive handoff.

## Music analysis and practice systems

| Product | Engineering core | Official entry |
| --- | --- | --- |
| **Session Craft** | Combines local HTDemucs stem separation with phase-vocoder time stretching, transposition, aligned loops, and session state for rehearsal without a cloud round trip. | [Repository](https://github.com/hannes-wan/session-craft-official) · [Product](https://hannes-software.com/session-craft/) |
| **Fretboard Lab** | Parses real chord symbols, generates voicings under physical fretboard constraints, and ranks candidates by position, span, difficulty, and open-string use across tunings. | [Repository](https://github.com/hannes-wan/fretboard-lab-official) · [Product](https://hannes-software.com/fretboard-lab/) |
| **Practice Rack** | Runs an ordered real-time DSP chain with deterministic nonlinear drive stages, cabinet impulse-response convolution, modulation, delay, reverb, FFT tuning, looping, and WAV capture. | [Repository](https://github.com/hannes-wan/practice-rack-official) · [Product](https://hannes-software.com/practice-rack/) |
| **LowEnd Forge** | Fuses Basic Pitch onset evidence with CREPE monophonic pitch tracking, then keeps octave correction, note boundaries, and four-string tablature open to musical review. | [Repository](https://github.com/hannes-wan/lowend-forge-official) · [Product](https://hannes-software.com/lowend-forge/) |
| **Backbeat Forge** | Moves from local separation and drum-hit evidence into editable five-line drum notation, two-voice percussion semantics, and General MIDI channel 10 export. | [Repository](https://github.com/hannes-wan/backbeat-forge-official) · [Product](https://hannes-software.com/backbeat-forge/) |

The model output is never treated as an oracle. Timing, confidence, pitches, kit pieces, voicings, loops, and notation remain visible enough to correct—because useful music software must respect the performance, not merely emit a file.

## Local clinic operations

| Product | Engineering core | Official entry |
| --- | --- | --- |
| **Dental Ark** | Keeps patient, appointment, visit, billing, and image records in a local SQLite workflow, with native FDI charting, explicit clinical states, and restorable manifest-backed backups. | [Repository](https://github.com/hannes-wan/dental-ark-official) · [Product](https://hannes-software.com/dental-ark/) |

Dental Ark treats data custody and recoverability as product behavior. Scheduling, chairside context, charting, checkout, balances, and backup verification belong to one coherent desktop record—not a pile of disconnected forms.

## What the public repositories contain

These are **proprietary product distribution and community repositories**, not source-code releases. Product source is developed in a private workspace. The public repositories provide:

- verified desktop releases and checksums;
- product documentation and honest capability boundaries;
- structured bug and feature-request intake;
- security-reporting and support guidance.

For product questions, use the relevant repository. For studio-wide context, visit [hannes-software.com](https://hannes-software.com/).
