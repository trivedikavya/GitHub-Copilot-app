# 🎈 GitHub Celebration Card Generator

> Built for **GitHub Copilot Day** using **GitHub Copilot** in VS Code.

An interactive, browser-based card generator built to celebrate developer milestones, achievements, and open-source contributions. Customize your profile, adjust card styling, toggle generative doodle effects, and export high-resolution PNG cards ready for social media sharing.

---

##  Features

- **Live Card Studio Preview:** Real-time side-by-side editing and rendering of your celebration card.
- **Custom Profile Details:** Upload your own photo, adjust position/zoom, and edit your Name, GitHub Handle, Role/Bio, and Custom Tagline.
- **Interactive Styling & Doodles:**
  - **Accent Colors:** Switch between classic GitHub Green, Terminal Cyan, and Open Source Violet.
  - **Doodle Density:** Toggle visual density modes (*Minimal*, *Medium*, *Crazy*).
  - **Photo Frame Shapes:** Switch between *Circle*, *Square*, and *Sticker* badge borders.
  - **Randomizer ("Surprise Me"):** Instantly generate randomized doodle layouts and color themes.
- **Export & Share Pipeline:**
  - One-click **1600 × 2000 PNG** export optimized for social media.
  - Copy ready-to-use captions straight to your clipboard.
  - Integrated web sharing options.

---

##  Built with GitHub Copilot

This project was built leveraging next-gen features in **GitHub Copilot**:

- **Restore Checkpoints & Thread Forking:** Reverted and branched chat sessions mid-build to experiment with card themes without losing context.
- **Custom Agent Configurations & Tool Permissions:** Fine-tuned agent access to local workspace files and terminal actions for rapid execution.
- **Voice-to-Text Dictation:** Used hands-free voice prompting directly inside the editor to describe UI changes naturally.

---

##  Tech Stack

- **Frontend:** HTML5, CSS3 (Custom Dark Theme & Glassmorphic Utilities), JavaScript / TypeScript
- **UI Components:** Responsive flex/grid container layout with real-time DOM updates
- **Canvas / Exporting:** Image rendering & canvas blob generation for high-density PNG downloads

