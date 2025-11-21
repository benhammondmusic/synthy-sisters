# 🎹 Synthy Sisters Piano Project

## 💡 Why I Built This

I created this project because I was looking for a **simple, ad-free virtual piano** for my younger girls to play on their devices, especially when using **headphones**. Most apps available were either cluttered with ads or too complicated, so I built this clean, focused, and fun musical toy just for them.

***

## ⚙️ How It Works

This project is built using only standard web technologies: HTML, CSS, and vanilla JavaScript.

* **Technology:** HTML5, CSS3, JavaScript (using the **Web Audio API**).
* **Sound:** Generates a basic, clean **sine wave** note, giving it a simple synth sound.
* **Starting the Sound:** The **"START PLAYING!"** button is essential. It performs the required step of initializing the sound engine (`AudioContext`), which modern mobile operating systems (like **iOS**) need before any audio can be played.

***

## 📱 Mobile Friendly Layout

The keyboard automatically adjusts its size and key count to be playable on different devices:

* **Small Screens (<700px):** The piano displays **15 white keys** (C3 up to C5). This makes the individual keys wider and easier for small fingers to tap.
* **Wide Screens (>700px):** The piano displays the full **18 keys**.
* **Screen Rotation:** If you rotate your phone or tablet, the keyboard automatically detects the change and redraws the keys to fit the new width.

***

## ▶️ Getting Started

1. Save the code as a file named `synthy-sisters-piano.html`.
2. Open the file directly in any web browser.

## ⚠️ Troubleshooting

* **No Sound on iPhone/iPad:** If you have sound issues after tapping the START button, check your device's physical **Silent/Ringer Switch** (on the side). If the switch is muted (showing orange), iOS may be blocking the web app's sound.
* **Initial Tap:** You **must** tap the **"START PLAYING!"** button first, or the piano keys will remain silent.
