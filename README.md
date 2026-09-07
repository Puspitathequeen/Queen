# 💖Unclickable no — Interactive Web Experience

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License: MIT](https://img.shields.io/badge/License-MIT-pink.svg?style=for-the-badge)
[![Instagram](https://img.shields.io/badge/Instagram-@the.cipher.stack-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/the.cipher.stack)

<p align="center">
  <strong>An adorable, interactive Valentine's Day web application with dynamic emotional progression, heart confetti, and a claimable Official Valentine Certificate complete with an interactive signature pad and cat paw stamp! 🐾✨</strong>
</p>

</div>

---

## ✨ Features

- 🐱 **Interactive Emotion Flow**:
  - Clicking **"No"** cycles through progressively sadder and pleading kitten GIFs (7 emotional stages).
  - The **"Yes"** button grows dynamically with each "No" click, making it irresistible to press!
- 💖 **Heart Confetti Explosion**:
  - Full-screen custom SVG heart-shaped confetti animation upon accepting.
- 📜 **Official "Valentine Partnership Certificate"**:
  - **Open / Close Toggle**: Revealed via a cute animated button after saying "Yes".
  - **Interactive Signature Pad**: Sign directly on screen using a mouse or touch/finger (mobile-friendly).
  - **🐾 "Stamp Paw" Button**: Stamps a realistic, adorable kitten paw print with toe beans onto the signature line.
  - **↺ Clear Signature Button**: Easily reset and re-sign anytime.
  - **Dynamic Date**: Auto-fills the current date formatted cleanly.
- 📱 **Fully Responsive & Modern Design**:
  - Built with **Tailwind CSS**, featuring soft pastel gradients, smooth transitions, and glassmorphism styling.
- 📸 **Social Integration**:
  - Sleek floating Instagram badge linked directly to [@the.cipher.stack](https://www.instagram.com/the.cipher.stack).

---

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/Ask-out-your-Valentine.git
cd Ask-out-your-Valentine
```

### 2. Run the Project
No build steps or dependencies required! Simply open `index.html` in your favorite web browser:

- **Windows**: Double-click `index.html` or run in terminal:
  ```powershell
  start index.html
  ```
- **VS Code Live Server**: Right-click `index.html` and select **"Open with Live Server"**.

---

## 📁 Project Structure

```text
├── images/
│   ├── image1.gif          # Cute kitten with flowers (Intro)
│   ├── image2.gif          # Sad kitten looking up
│   ├── image3.gif          # Begging kitten
│   ├── image4.gif          # Heartbroken kitten
│   ├── image5.gif          # Crying kitten
│   ├── image6.gif          # Devastated kitten
│   └── image7.gif          # Celebrating happy kitten (Success)
├── index.html              # Main single-page application
├── LICENSE                 # MIT License
└── README.md               # Project documentation
```

---

## 🛠️ Tech Stack

- **HTML5 & CSS3**: Semantic layout and custom keyframe animations (`bounce`, `fadeInUp`, `stampPop`).
- **[Tailwind CSS (CDN)](https://tailwindcss.com/)**: Utility-first styling, pastel color palettes, and responsive layouts.
- **[Canvas Confetti](https://www.npmjs.com/package/canvas-confetti)**: Custom vector heart-shape confetti physics.
- **HTML5 Canvas API**: Real-time 2D drawing and coordinate mapping for signatures and paw stamping.

---

## 🎨 Customization

You can easily customize the text, messages, and dates inside `index.html`:

- **Change "No" button messages**:
  Edit the `NO_BUTTON_MESSAGES` array in `index.html`:
  ```javascript
  const NO_BUTTON_MESSAGES = [
    'No',
    'Are you sure?',
    'Pookie please',
    "Don't do this to me :(",
    "You're breaking my heart",
    "I'm gonna cry...",
  ];
  ```
- **Change the Certificate Terms**:
  Modify the text inside `<div id="certificateCard">...</div>` in `index.html`.
- **Change Images**:
  Replace the GIFs inside the `images/` directory with your own GIFs or photos while keeping the same filenames (`image1.gif` - `image7.gif`).

---

## 👨‍💻 Author

Created with ❤️ by **[@the.cipher.stack](https://www.instagram.com/the.cipher.stack)**

Follow on Instagram for more creative tech projects and web experiments!

---

## 📄 License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and share it with your special someone! 💕
