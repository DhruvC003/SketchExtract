# SketchExtract

**Transform your sketches into realistic faces with AI.** 🎨✨

SketchExtract is a creative mobile application that lets users draw a face freehand and transform the sketch into a realistic face rendering using an AI-powered image-processing backend.

## Preview

![SketchExtract app and AI transformation workflow](assets/results-and-discussion.png)

## Features

- **Interactive drawing canvas** — Draw using your finger or a stylus.
- **AI-powered sketch transformation** — Send line-art sketches to the backend and receive realistic face renderings.
- **Loading feedback** — Displays progress while the image is being processed.
- **Configurable API endpoint** — Update the backend URL from the settings menu.
- **Clean, modern interface** — Minimal design with a light-blue theme.

## How It Works

1. Draw a face on the SketchExtract canvas.
2. Submit the sketch to the configured backend API.
3. The backend processes the drawing using the AI image-generation model.
4. View the generated face in the app.

## Tech Stack

| Component | Technology |
|---|---|
| Mobile frontend | Flutter |
| Programming language | Dart |
| Backend | Custom image-processing API |
| AI processing | AI model accessed through the backend API |

## Getting Started

### Prerequisites

- Flutter SDK
- Dart SDK
- A running SketchExtract-compatible image-processing API

### Installation

```bash
git clone https://github.com/DecentCraze/SketchExtract.git
cd SketchExtract
flutter pub get
```

### Configure the Backend

Run or deploy your image-processing API, then open the app's settings and enter the API endpoint. Make sure the mobile device or emulator can reach that endpoint.

### Run the App

```bash
flutter run
```

## Research Paper

Read the paper: [SketchExtract Research Paper](https://sketchextract.tiiny.site)

## Author

**Dhruv C**

- GitHub: [@DecentCraze](https://github.com/DecentCraze)

---

*Note: Update the repository URL above if your GitHub repository uses a different name.*
