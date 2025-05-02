# SketchExtract  
Create and transform your drawings into IRL faces with SketchExtract! 🎨✨

---

## Overview  
**SketchExtract** is a creative app that lets you draw freehand sketches and transform them into realistic face renderings using AI-powered image processing. Built with Flutter, it connects to a custom backend API to generate stunning results from simple line art.

---

## Features  
- 🖌️ **Interactive Drawing Canvas** — Draw with your finger or stylus on a smooth, responsive canvas.  
- 🔁 **Real-Time Image Processing** — Send your sketch to an AI backend and receive a realistic face transformation.  
- 🔄 **Loading Indicator** — Beautiful progress UI while your image is being processed.  
- ⚙️ **Custom API Endpoint** — Change the backend URL from the settings menu.  
- 🌈 **Clean & Modern UI** — Elegant, minimalist design using a calming light blue theme.

---

## Tech Stack  
- **Frontend:** Flutter  
- **Backend:** Custom API for image processing  
- **Image Processing:** AI model (handled via the API)

---

## Getting Started  

### Prerequisites  
- Flutter SDK  
- Dart SDK  
- A working image-processing API (you can deploy your own or use an existing one)

### Installation  

```bash
git clone https://github.com/your-username/SketchExtract.git
cd SketchExtract
flutter pub get

🔧 Configuration
Edit the API URL in your Flutter code:

dart
Copy
Edit
String _apiUrl = 'https://your-api-url.com';
You can also change this in the app's Settings (gear icon).

▶️ Run the App
bash
Copy
Edit
flutter run
📲 Usage Instructions
✏️ Draw – Sketch a face or idea using the canvas at the bottom.

⭐ Generate – Tap the star icon to submit your sketch to the backend.

🖼️ View Result – The transformed image appears at the top.

🔄 Reset – Clear the canvas using the refresh icon.

⚙️ Change API URL – Update the backend endpoint in Settings.

🔌 API Endpoint
POST /process-image
Request:

Content-Type: multipart/form-data

Body: A PNG image of your sketch

Response:

A generated image (preferably JPG format)

Sample payload:

http
Copy
Edit
POST /process-image
Content-Type: multipart/form-data
Body: file=<your_sketch.png>
🎨 Customization
App Theme Color: Modify in main.dart (default: #bfd7ed)

API URL: Update it dynamically in the app's settings

📝 License
This project is licensed under the MIT License – see the LICENSE file for details.

🤝 Contributing
We welcome contributions!
To contribute:

Fork the repo

Create a new branch (git checkout -b feature/your-feature)

Commit your changes (git commit -m 'Add feature')

Push to the branch (git push origin feature/your-feature)

Open a pull request

### 📬 Contact
Created by Dhruv C
GitHub: @DecentCraze
