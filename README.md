<div align="center">

# 💊 MedScheduler | Neural Vitality

### A futuristic AI-powered medical interface for prescription scanning and automated medication scheduling

[![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.8-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-6-646CFF?logo=vite&logoColor=white)](https://vitejs.dev/)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-4-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Gemini API](https://img.shields.io/badge/Google-Gemini%20API-4285F4?logo=google&logoColor=white)](https://ai.google.dev/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

<br />

<!-- 🖼️ MAIN DEMO SCREENSHOT — replace this with a real screenshot or GIF of your app's home screen -->
<img src="https://drive.google.com/file/d/1LnJ_dzQU8ZaklRPFBumdGNVu7oFKVbnb/view?usp=sharing" alt="MedScheduler Home Screen" width="850" />

</div>

<br />

## ✨ What is MedScheduler?

**MedScheduler** turns a photo of a handwritten or printed prescription into an automated medication schedule — no manual data entry required.

Point your camera at a prescription, and MedScheduler reads it, extracts the medicine names, dosages, and timings using AI, and builds a personalized reminder schedule so you never miss a dose. Built for patients, caregivers, and anyone tired of squinting at doctor handwriting.

<br />

## 🎬 See It In Action

<!-- 🖼️ Replace each placeholder below with an actual screenshot or short GIF of that screen -->

<table>
  <tr>
    <td align="center" width="33%">
      <img src="https://via.placeholder.com/300x550/0f172a/38bdf8?text=Scan+Prescription" width="260" /><br />
      <b>1. Scan a Prescription</b><br />
      <sub>Use your camera to capture the prescription</sub>
    </td>
    <td align="center" width="33%">
      <img src="https://via.placeholder.com/300x550/0f172a/38bdf8?text=AI+Extraction" width="260" /><br />
      <b>2. AI Extracts the Details</b><br />
      <sub>Gemini reads medicine names, dosage & timing</sub>
    </td>
    <td align="center" width="33%">
      <img src="https://via.placeholder.com/300x550/0f172a/38bdf8?text=Auto+Schedule" width="260" /><br />
      <b>3. Get Your Schedule</b><br />
      <sub>An automated reminder schedule, ready to go</sub>
    </td>
  </tr>
</table>

<br />

## 🚀 Key Features

- 📷 **Camera-based prescription scanning** — no typing, just point and capture
- 🤖 **AI-powered extraction** — Google Gemini API reads and structures prescription data automatically
- ⏰ **Automated medication scheduling** — reminders generated instantly from scanned data
- 🎨 **Modern, futuristic interface** — smooth animations and a clean medical-tech aesthetic
- ⚡ **Fast and lightweight** — built on Vite for near-instant load times
- 🔐 **Privacy-first** — prescription data is processed for scheduling only, nothing stored beyond what you choose to keep

<br />

## 🛠️ Built With

| Layer | Technology |
|---|---|
| **Frontend** | React 19 + TypeScript |
| **Styling** | Tailwind CSS 4 |
| **Build Tool** | Vite 6 |
| **AI Engine** | Google Gemini API (`@google/genai`) |
| **Animations** | Motion |
| **Icons** | Lucide React |
| **Backend** | Express + dotenv |

<br />

## 📲 How to Use It

1. **Open the app** and grant camera access when prompted (needed to scan prescriptions).
2. **Point your camera** at a prescription — printed or handwritten.
3. **Capture the image.** MedScheduler sends it to the Gemini API, which extracts medicine names, dosages, and timing instructions.
4. **Review the extracted schedule** — double-check the AI got everything right (always good practice with any medical tool).
5. **Confirm**, and your personalized medication schedule is created — ready to remind you when it's time for your next dose.

<br />

## 💻 Getting Started (Run It Yourself)

Want to run MedScheduler on your own machine? Here's how:

### Prerequisites

- [Node.js](https://nodejs.org/) installed on your machine
- A free Gemini API key from [Google AI Studio](https://aistudio.google.com/app/apikey)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/medscheduler.git
cd medscheduler

# 2. Install dependencies
npm install

# 3. Set up your environment variables
cp .env.example .env.local
```

Now open `.env.local` and add your own Gemini API key:

```env
GEMINI_API_KEY=your_gemini_api_key_here
```

```bash
# 4. Run the app
npm run dev
```

The app will start locally — open the URL shown in your terminal (typically `http://localhost:5173`) to see it in action.

<br />

## 📌 Roadmap

- [ ] Add support for multi-language prescriptions
- [ ] Push notifications for medication reminders
- [ ] Export schedule to Google Calendar
- [ ] Caregiver/family shared-view mode

<br />

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](../../issues) or open a pull request.

<br />

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

<br />

## 📬 Contact

**Omkar Divekar**
[LinkedIn](https://www.linkedin.com/in/omkardivekar-144903247) · [Email](mailto:omkarrdivekar2194@gmail.com)

<br />

<div align="center">
<sub>Built with care to make managing medications a little less stressful.</sub>
</div>
