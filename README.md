# 🎨 3D Dragon Carousel | CSS-Only Animated Showcase 🐉✨
🌟 Overview
This project is a stunning CSS-only 3D rotating carousel featuring majestic dragon illustrations. With smooth perspective animations, a stylish futuristic grid background, and a minimal yet powerful design, this web component is perfect for showcasing artwork, digital assets, or creative portfolios.

# 🚀 Features
✔️ CSS-Only Animation – No JavaScript required!
✔️ 3D Perspective Slider – Immersive depth effect with smooth rotation.
✔️ Custom Background Grid – A sleek, futuristic aesthetic.
✔️ Responsive Design – Adapts to different screen sizes.
✔️ Stylized Typography – Uses ICA Rubrik and Poppins fonts for a modern touch.

🎥 Live Preview
🔗 Check it out! (Add your live demo link here)

# 🛠️ Technologies Used
HTML5 – Structure of the web page

CSS3 – Advanced animations, 3D transforms, and grid effects

GSAP / Locomotive Scroll (optional) – Enhance animations (if extended)

# 🎨 Customization
To modify the images in the slider, replace the files in the images/ folder:

bash
Copy
Edit
/images/dragon_1.jpg
/images/dragon_2.jpg
...
/images/dragon_10.jpg
Modify animation speed in style.css:

css
Copy
Edit
@keyframes autoRun {
    from {
        transform: perspective(1000px) rotateX(-16deg) rotateY(0deg);
    }
    to {
        transform: perspective(1000px) rotateX(-16deg) rotateY(360deg);
    }
}
Adjust 20s to change rotation speed.

# 🏆 Why You'll Love It
🎭 Visually Stunning – A unique UI element that grabs attention.
🎮 Interactive & Engaging – Perfect for creative portfolios.
📱 Mobile-Friendly – Works well on all screen sizes.

# 💡 Future Enhancements
🔹 Add user interactivity (mouse drag/swipe)
🔹 Integrate JavaScript for dynamic content loading
🔹 Implement GSAP for smoother transitions

# 🤝 Contributors
👨‍💻 Gouti Dev - Web Designer & Developer

🔥 Star this repo if you like it & feel free to contribute! 🚀
