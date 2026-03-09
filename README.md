# 📸 Web Photo Booth (Sky Blue Edition)

A modern, browser-based 4-shot photo booth application featuring a clean sky blue theme and a minimalist, high-performance UI.

**🔗 Live Demo:** [https://web-photoboost.vercel.app/](https://web-photoboost.vercel.app/)

## 🛠️ Features

- **📸 4-Shot Sequence:** Automated capture system that takes 4 consecutive shots with a built-in countdown.
- **🔹 Sky Blue Minimalist Theme:** A professional UI design using a sky blue palette, 3D interaction elements, and a clean layout.
- **⚡ Dynamic UI Components:** Optimized animations and floating visual elements for an engaging user experience.
- **🖼️ Photo Strip Generator:** Automatically processes and combines 4 individual captures into a single vertical photo strip with custom overlays.
- **💾 Instant Export:** Fast download functionality to save the final photo strip directly to your device.

## 🚀 How to Use

1. Access the application via a web browser (Camera access required).
2. Grant Camera Permissions when prompted.
3. Click "Open Camera" to initialize the standby mode.
4. Prepare your pose and trigger the "Capture Now" button.
5. The system will manage a 3-second countdown for each of the 4 shots.
6. Once processing is complete, a final photo strip will be generated.
7. Click "Save Photo" to download the high-resolution output.

## 💻 Tech Stack

- **HTML5 & CSS3:** Core structure and advanced styling.
- **Tailwind CSS:** Utility-first framework for responsive and modern UI layout.
- **Vanilla JavaScript:** Handles camera control (MediaDevices API) and image processing (Canvas API).
- **Lucide Icons:** For clean, minimalist vector icons.
- **Google Fonts:** Utilizing modern typography for improved readability.

## 🎨 Customization

The project is designed for easy modification via `index.html`:

- **Styling:** Adjust colors and layout using Tailwind CSS classes.
- **Core Logic:** Modify the `combinePhotosAndShowResult()` function to change the photo strip dimensions or text overlays.
- **Visuals:** Toggle or update floating elements within the animation configuration.

---

*Efficient, clean, and ready for use. Build your own digital photo booth today.*
