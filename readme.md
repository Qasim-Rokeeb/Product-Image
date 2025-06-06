
# 👕 Product Image Preview – Day 21 of 30 Days of JavaScript

An interactive **product detail page** built with **HTML**, **CSS**, and **JavaScript**, where users can preview different images of a product, select sizes, choose colors, and input quantity – just like a real e-commerce platform.

---

## ✨ Features

- 🖼️ Live image switching via interactive gallery buttons
- 📏 Size selection with custom radio buttons
- 🎨 Color selection with animated feedback
- 🔢 Quantity input
- 🛒 "Buy Now" button with modern UI

---

## 📸 Preview

Here’s a look at the Product Page:

![App Preview](https://raw.githubusercontent.com/Qasim-Rokeeb/Product-Image/main/screenshot.png)

---

## 🌐 Live Demo

🔗 [View Live Project](https://qasim-rokeeb.github.io/Product-Image)

---

## 🧱 Built With

- HTML5
- CSS3 (modern layout and style)
- JavaScript (image switching logic)

---

## 🧠 How It Works

- The main product image is updated when a thumbnail dot is clicked.
- CSS classes (`.active`) visually highlight the selected dot.
- Color selections use a custom radio styling and apply border effects.
- JavaScript updates the image source dynamically:

```js
btn[0].onclick = function () {
  productImg.src = "images/image1.png";
  for (bt of btn) {
    bt.classList.remove("active");
  }
  this.classList.add("active");
}
```

---

## 📁 Project Structure

```bash
Product-Image-Preview/
├── index.html         # HTML structure for product display
├── style.css          # Styling for layout, buttons, and interactivity
├── script.js          # Handles image switching and active state
├── images/            # Folder with image1.png, image2.png, image3.png
├── screenshot.png     # Project preview image
└── README.md
```

---

## 🧵 What I Learned

- Managing dynamic image changes in JavaScript
- Styling interactive radio buttons with CSS only
- Using flex layout for responsive product page design
- Highlighting selected elements with `.active` class management

---

## 📅 Challenge

This is **Day 21** of my **30 Days of JavaScript** challenge.  
Follow along for more UI mini-projects 👇

📲 [@qasimrokeeb](https://x.com/qasimrokeeb)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).
````

