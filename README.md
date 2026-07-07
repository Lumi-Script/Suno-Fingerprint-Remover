# Audio Fingerprint Studio 🎵🕵️‍♂️

Advanced in-browser neural processing for watermark removal, detection, and forensic analysis. This tool allows you to strip AI audio fingerprints and hidden steganography from audio files entirely in your browser using the Web Audio API.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com/Lumi-Script/Suno-Fingerprint-Remover)

## Features ✨

- **Remover Engine:** Strip away watermarks using different approaches:
  - *Standard*: Balanced approach, preserves high fidelity.
  - *Aggressive*: Maximum removal at a slight cost to quality.
  - *SOTA / Next-Gen*: State-of-the-art neural cleaning algorithms with micro-timing jitter and natural variation injection.
- **Detector Engine:** Detect hidden signatures with:
  - *Suno Detector*: Optimized for detecting Suno AI signatures.
  - *Advanced Steganography*: Deep scan for hidden sub-audible patterns.
  - *Quick Comparator*: Compare against known watermark databases.
- **In-Browser Processing:** Fast, private, and secure processing on your own device using the Web Audio API. No audio data is uploaded to external servers.
- **Export Options:** Supports exporting processed files to WAV or MP3 formats with automatic bitrate matching.
- **Deep Analysis & Harmonic Preservation:** Tools for spectral and phase analysis while compensating for high-frequency cuts.

## How to Use 🚀

1. **Select Mode:** Choose between **Remover** (to clean an audio file) or **Detector** (to analyze an audio file for watermarks).
2. **Configure Settings:** 
   - Pick the desired engine type (Standard/Aggressive/SOTA for Remover, or Suno/Advanced/Comparator for Detector).
   - Toggle advanced options like "Deep Analysis" and "Preserve Harmonics".
3. **Upload Audio:** Drag and drop your audio file (`.mp3` or `.wav`) into the Processing Space, or click to browse.
4. **Process:** Click **Start Removal** or **Run Detection**.
5. **Review & Download:** Review the analysis results and click **Download Processed File** to save your clean audio.

## Local Development 💻

This project is built with React and Vite.

### Prerequisites

- Node.js (v18 or higher recommended)
- npm

### Installation & Setup

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm run dev
   ```

3. Build for production:
   ```bash
   npm run build
   ```

## Tech Stack 🛠

- **Framework:** React + TypeScript
- **Bundler:** Vite
- **Styling:** Vanilla CSS
- **Audio Processing:** Web Audio API, `lamejs`
- **Icons:** Lucide React
