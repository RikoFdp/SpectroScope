🎵 SpectroScope
SpectroScope is a high-fidelity, completely offline acoustic spectrum analyzer built directly for the modern web and mobile devices.
Inspired by the classic desktop tool Spek, SpectroScope allows audiophiles, sound engineers, and music collectors to instantly visualize the frequency spectrum of their audio files to verify true lossless quality (e.g., distinguishing a true FLAC from a transcoded MP3).

✨ Features
- Advanced Spectrogram Visualization: Uses a custom-built, chunk-based Fast Fourier Transform (FFT) JavaScript engine that processes heavy audio files smoothly without crashing mobile browsers.
- Deep MediaInfo Extraction: Reads embedded metadata to provide thorough technical details (Bit rate, Sample rate, Channel layout, Compression mode, and exact Image dimensions) separated into clean General, Audio, and Image tabs.
- Smart Quality Badges: Automatically calculates acoustic density to award files with HI-RES, CD QUALITY, or STANDARD badges (inspired by Tidal/Qobuz).
- Integrated Music Player: Includes a sleek, touch-friendly media player that extracts and displays embedded high-resolution album artwork on the fly.
- 100% Privacy Focused: Everything happens directly in your device's memory. No audio files are ever uploaded to any server.
- Progressive Web App (PWA): Installable directly to your home screen. It includes a Service Worker, meaning once loaded, it works completely offline.

🚀 How to Use
You do not need to download or install any software to use SpectroScope.
1. Visit the live app here: Launch SpectroScope
2. Drag and drop (or tap to select) any audio file (.flac, .wav, .mp3, .m4a, etc.).
3. Wait a moment for the engine to paint the frequencies.
4. Read the Graph:
- A true lossless file (like CD-quality FLAC) will show frequencies reaching all the way up to ~22kHz.
- A lossy file (like a 320kbps MP3) will show a hard, flat horizontal cut-off around 20kHz.

📱 Installing as an App
Because SpectroScope is a PWA, you can install it natively on your phone or desktop:
- Android / Chrome: Open the site, tap the three-dot menu ⋮, and select "Install app" or "Add to Home screen".
- iOS / Safari: Open the site, tap the Share icon, and select "Add to Home Screen".
(Note: If you want to compile this into a traditional .apk file for the Google Play Store, the repository is fully compatible with PWABuilder.)

🛠️ Tech Stack
Built entirely from scratch using raw web technologies to ensure a lightweight footprint:
- HTML5 / CSS3
- Vanilla JavaScript (ES6+) - For the custom FFT math engine and audio decoding.
- Tailwind CSS - Pulled via CDN for rapid, responsive, modern UI styling.
- jsmediatags - For robust ID3/MP4/FLAC metadata extraction.

🙏 Acknowledgments
Massive inspiration taken from Alexander Kojevnikov's Spek, the gold standard for desktop acoustic spectrum analysis.
