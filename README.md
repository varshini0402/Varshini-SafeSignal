# SafeSignal

Android personal safety app with AI sound detection and live location sharing.

**Course:** MAL3018 Computing Project, BSc (Hons) Computer Science (Software Engineering)
**Student:** Varshini (ID: BSSE2506011)
**Supervisor:** Mr Eric Kong Kok Wah
**Status:** Proposal stage (development starts November 2026)

## About

SafeSignal helps people who may not be able to reach their phone or make a sound in an emergency. Existing safety apps (Save Me 999, bSafe, UrSafe) all need the user to start the alert themselves. SafeSignal can also detect distress sounds automatically and alert the user's own emergency contacts, who can watch live without installing the app.

## Main Features

- **One-touch SOS:** sends live GPS location to user-assigned emergency contacts by SMS link.
- **AI Listening Mode:** detects glass breaking and screaming on the phone (YAMNet with TensorFlow Lite), then starts SOS after a 5 to 10 second cancellation window.
- **Live location and audio-video:** contacts open a web link and see the live map and stream, with no app install needed.
- **Decoy calculator:** a working calculator that hides the app, opened with a hidden code.
- **Nearest police station lookup** using the Google Places API.

## Tech Stack

| Part | Technology |
|---|---|
| Android app | Java, Android Studio |
| Backend | Firebase Realtime Database, Firebase Hosting |
| Live audio-video | Agora |
| Sound detection | TensorFlow Lite, YAMNet |
| Web viewer page | HTML, CSS, JavaScript, Google Maps JavaScript API |
| Design | Figma |

## Repository Structure

```
SafeSignal/
├── docs/          Proposal, Gantt chart, diagrams, comparison table
├── design/        Figma screens
├── app/           Android app (Java), coming in development phase
└── web-viewer/    Web viewer page (HTML, CSS, JavaScript), coming in development phase
```

## Timeline

14 September 2026 to 15 April 2027. See `docs/` for the Gantt chart.

## Note

API keys (Firebase, Agora, Google Maps) are not stored in this repository.
