# 🎁 Birthday Gift Animation 🎂

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white)

A beautiful, interactive, and fully responsive animated birthday greeting website. Built with love using HTML, CSS, and JavaScript.

## ✨ Features

- **🎉 Animated Greetings:** Watch as the "Happy Birthday" text delightfully bounces into view with staggered CSS animations!
- **💌 Interactive Letter:** A beautifully styled letter box that opens up to reveal a personalized, heartfelt message alongside cute Giphy stickers.
- **💖 Interactive Heart Cursor:** Custom trailing heart animations that follow your mouse cursor everywhere it goes!
- **📱 Fully Responsive:** Works perfectly on desktops, tablets, and mobile devices. 
- **🎈 Floating Elements:** Floating balloons, stars, and flowers create a festive and joyous atmosphere.
- **🎨 Custom Typography:** Beautifully paired Google Fonts (Dancing Script, Sriracha, Titan One, Coiny, Nerko One) to give a premium feel.

## 🚀 Live Demo

You can view the live deployment of this project at:
**[Insert Your Netlify/Vercel Link Here]**

## 🛠️ Technologies Used

- **HTML5:** For the structural markup of the website.
- **CSS3:** For extensive animations, flexbox layouts, media queries, and beautiful linear-gradients.
- **JavaScript (Vanilla & jQuery):** Used for timing the text animations (typing effect), handling the popup box, and driving the interactive heart cursor.
- **FontAwesome:** For intuitive UI icons.
- **Google Fonts:** To make the text pop!

## 📂 Project Structure

```text
📁 Birthday-Gift-Animation
├── 📄 index.html      # The main HTML structure
├── 🎨 style.css       # All styling and keyframe animations
└── 📁 Images          # Contains all static assets (balloons, hats, etc.)
```

## 💻 Running Locally

To run this project locally, simply follow these steps:

1. **Clone the repository** (or download the ZIP file).
   ```bash
   git clone https://github.com/YourUsername/Birthday-Gift-Animation.git
   ```
2. **Navigate to the directory**:
   ```bash
   cd Birthday-Gift-Animation
   ```
3. **Open `index.html`** in your favorite web browser!
   *(You can also use an extension like VS Code Live Server for hot reloading).*

## 🎨 Customization

Want to use this for someone else? It's incredibly easy to customize!

1. **Change the Name & Date:**
   Open `index.html` and scroll down to the bottom `<script>` tag. Modify the `datetxt`, `datatxtletter`, and `titleLetter` variables:
   ```javascript
   let datetxt = "18 November 2002"; // Change Date
   let datatxtletter = "Your custom birthday message goes here! 💕"; // Change Message
   let titleLetter = "Happy Birthday [Name]"; // Change Name
   ```
2. **Change the Name in the main UI:**
   In `index.html`, look for the `<h1 class="birthday">` tags inside the `<div class="title">` container and update the individual `<span>` elements to spell out the new name!
3. **Change the Images:**
   Replace the images in the `/Images/` directory to personalize the avatars and balloons!

## 📸 Screenshots

*(You can add screenshots of your running application here!)*

| Main Screen | Open Letter |
| ----------- | ----------- |
| <img src="[Link to screenshot 1]" width="400"> | <img src="[Link to screenshot 2]" width="400"> |

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! 
Feel free to check out the [issues page](https://github.com/YourUsername/Birthday-Gift-Animation/issues).

## 📝 License

This project is licensed under the MIT License - feel free to use it, modify it, and share it with your loved ones! ❤️

---
*Made with ❤️ and Code.*
