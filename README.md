# 🌈 GradientForge – Interactive Gradient Theme Generator

**GradientForge** is a beautifully designed, interactive tool that lets users generate, preview, and copy custom CSS gradients in real time.  
Built with **HTML**, **Tailwind CSS**, and **JavaScript**, it offers a seamless way to craft gradient backgrounds for websites, apps, or UI components — with support for linear, radial, and conic gradients.

[🔗 Live Demo](https://nft-website-custom-41u9.vercel.app/) &nbsp; | &nbsp; [📂 Source Code](https://github.com/deca-hue/gradient-theme-generator)

---

## 🎨 What It Does

- 🧠 **Live gradient preview** as you adjust colors
- 🌈 Supports **linear, radial, and conic gradients**
- 🎯 Lets you set direction, angle, and position
- 📋 **Copy-to-clipboard** ready CSS output
- 💅 Easily customizable and exportable background themes
- 🧊 Styled with Tailwind + animations for a modern feel

---

## 🧠 Why Build This?

GradientForge is more than a UI toy — it’s a productivity and design tool.  
It helps:

- **Frontend developers** preview background styles live  
- **UI designers** create aesthetic palettes  
- **Web creators** generate ready-to-use CSS snippets  
- **Design systems** test visual variants quickly

This project demonstrates your ability to merge **practical tools** with **aesthetic design** and dynamic **JavaScript logic**.

---

## ✨ Features Breakdown

| Feature                  | Description |
|--------------------------|-------------|
| 🎛 Interactive UI         | Users control direction, type, and colors |
| 📋 Copy CSS Output        | One-click copy of final CSS code |
| 🖼 Live Background Preview| Instantly updates as changes are made |
| 📱 Mobile Friendly        | Fully responsive with Tailwind CSS |
| 🔄 Random Gradient Button | Inspires creativity with random styles |
| 📁 Export Snippet *(optional)* | Save CSS snippet locally (planned) |

---

## 🛠 Built With

| Tech              | Role                            |
|-------------------|---------------------------------|
| **HTML5**         | Markup and layout                |
| **Tailwind CSS**  | Responsive utility-first styling |
| **JavaScript (ES6)**| Interactivity and gradient logic |

---

## 📁 Folder Structure

💡 Use Cases
🎨 Web designers creating modern UIs

🧑‍💻 Developers customizing app themes

🪄 UI libraries offering color customization

🧪 Rapid prototyping and palette testing

💼 Personal or freelance portfolios

🔮 Future Enhancements
🌗 Dark mode toggle

🧾 Gradient history with localStorage

🖌 Tailwind class code export (bg-gradient-to-r etc.)

🎓 Export as image background or CSS file

🎨 Color harmony presets (analogous, triadic, etc.)

🧠 Logic Highlights
js
Copy
Edit
const color1 = document.getElementById("color1").value;
const color2 = document.getElementById("color2").value;
const angle = document.getElementById("angle").value;

const gradient = `linear-gradient(${angle}deg, ${color1}, ${color2})`;

document.getElementById("preview").style.background = gradient;
document.getElementById("css-output").value = `background: ${gradient};`;
Includes:

Live DOM updates

Gradient type switching

Clipboard support with navigator.clipboard.writeText()

📜 License
Licensed under the MIT License.
Free to use, remix, or build upon.

👨‍🎨 Author
Created by Your Name
Frontend Developer & Creative Tools Builder

📧 Email: mwas9611@gmail.com
🌐 Portfolio: https://deca-hue.github.io/designsv

“Design faster. Preview smarter. GradientForge helps your colors flow.” – GradientForge

yaml
Copy
Edit

---

✅ Want to level this up?

I can help you:
- Convert it into a React/Vue component  
- Add Tailwind class export (`bg-gradient-to-r from-[#fff] to-[#000]`)  
- Let users export preset themes or color palettes  
- Make it installable as a PWA  

Let me know and I’ll expand it!
