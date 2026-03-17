# SnapAndPlay.lua for AnkuLua

**Snap and Play** is a high-performance visual automation engine for Android. Unlike traditional macro recorders that rely on static screen coordinates, Snap and Play uses **Computer Vision (CV)** to "see" and interact with UI elements in real-time. 

This script bridges the gap between simple clickers and complex programmed bots, allowing anyone to create resilient automation without writing a single line of code.

---

## 🚀 Key Features

* **No-Code Scripting:** Create complex workflows simply by "snapping" images of the buttons or icons you want to interact with.
* **Visual Logic Engine:** The script intelligently waits for images to appear, handling game lag, network delays, or unexpected UI shifts automatically.
* **Smart Optimization:** Built-in algorithms for duplicate image detection and smart reordering to ensure maximum speed and minimal CPU overhead.
* **Safe by Design:** Uses randomized click offsets and human-like delays to mimic natural user interaction and minimize detection risks.
* **Open Source:** Highly extensible and customizable for power users who want to build upon the core logic.

---

## 🛠 How It Works

1.  **Record:** Open AnkuLua and run `snapAndPlay.lua`. Tap your target buttons while the screen highlights yellow to capture the image assets.
2.  **Logic Generation:** The script automatically generates a `.luar` file that contains the visual logic and image references.
3.  **Play:** Run the generated script. AnkuLua will now "watch" the screen and execute actions only when the target images are detected.

---

## 📥 Installation

1.  Download and install [AnkuLua](https://ankulua.boards.net/thread/1395/ankulua-trial-apk-download) on your Android device (or emulator).
2.  The build-in `snapAndPlay.lua` file is already there.
3.  Select the script within the AnkuLua app and follow the on-screen prompts to start recording. Stop the script to stop the recording.
4.  Play the snapAndPlay.lua script and choose playback to play the recorded script.
5.  You can choose the expand the recorded script if missing something at previous recording.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! If you have ideas for optimization or new features, feel free to open an issue or submit a pull request.

---

**Official Thread & Support:** [AnkuLua Forum - Snap and Play](https://ankulua.boards.net/thread/326/script-most-games-snap-play)
