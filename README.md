# Recall (iOS + Meta Ray-Ban Display)

Smart glasses that remember the people you meet. This repo is the iOS companion app that drives the **Meta Ray-Ban Display** glasses for Recall.

**1st Place, Open/Fintech Track, JacHacks SF (Jul 2026)** · [Devpost](https://devpost.com/software/reminisense) · Backend: [ReminiSense](https://github.com/arshmeets/ReminiSense)

Built with Arshmeet Sodhi, Likhith Ramesha and Aswath Jacob.

## What it does

- Streams the glasses camera and mic to the backend while you talk to someone
- Captions the conversation on the in-lens display
- Recognizes a face you have met before and shows their card: name, role, what they are working on, and what you left open
- Answers questions like "who was raising a seed round?" hands free, with a Neural Band pinch to navigate

The backend (Jac) stores your network as a graph of people, conversations and follow ups; this app is the eyes, ears and display.

## Stack

Swift · SwiftUI · Meta Wearables Device Access Toolkit 0.8 · XcodeGen

## Build

```bash
brew install xcodegen
xcodegen generate
open ReminiSense.xcodeproj
```

Requires a Meta Ray-Ban Display paired through the Meta AI app with Developer Mode enabled. Point the app at your own ReminiSense backend from the Connect screen.
