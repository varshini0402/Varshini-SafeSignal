# SafeSignal: An Android Personal Safety Application with On-Device AI Distress Sound Detection and Live Location Sharing

**Student:** Varshini Seger (BSSE2506011)
**Supervisor:** Mr Eric Kong Kok Wah
**Course:** MAL3018 Computing Project, BSc (Hons) Computer Science (Software Engineering), University of Plymouth
**Status:** Proposal stage. Development starts in November 2026.

## Project Vision

SafeSignal is an Android personal safety application for people who may not be able to reach their phone, unlock it, or make a sound when they are in danger, such as those living alone or facing domestic abuse or stalking. Existing apps (Save Me 999, bSafe, UrSafe) all need the user to start the alert themselves, and none can hide itself or detect danger passively.

SafeSignal will listen for distress sounds such as glass breaking and screaming on the phone itself, using the pretrained YAMNet model, and start an alert after a 5 to 10 second cancellation window. A one-touch SOS button will also be available. When an alert starts, the app sends the user's live location and live audio and video to the user's own emergency contacts through an SMS link that opens in a browser, so the contacts do not need to install the app. A working decoy calculator, opened with a hidden code, keeps the app hidden from anyone who inspects the phone.

## Main Features

- One-touch SOS with live GPS location sent to user-assigned emergency contacts
- AI Listening Mode (YAMNet with TensorFlow Lite) with a 5 to 10 second cancellation window
- Live location, audio and video viewed through a web link, with no app install needed
- Decoy calculator with a hidden code
- Nearest police station lookup, silent mode, English and Malay support

## Tech Stack

| Part | Technology |
|---|---|
| Android app | Kotlin, Android Studio |
| Backend | Firebase Realtime Database, Firebase Hosting |
| Live audio-video | Agora |
| Sound detection | TensorFlow Lite, YAMNet |
| Web viewer page | HTML, CSS, JavaScript, Google Maps JavaScript API |
| Design | Figma |

## Timeline

14 September 2026 to 1 April 2027 (ePortfolio), with the Showcase and Viva on 6 April 2027. Development follows Agile with two-week sprints.

*API keys (Firebase, Agora, Google Maps) are not stored in this repository.*
