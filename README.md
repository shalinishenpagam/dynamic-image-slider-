🎞️ Dynamic Image Slider

A fully responsive Dynamic Image Slider built using HTML, CSS, and JavaScript.
This project demonstrates how to create an interactive image carousel that supports automatic sliding, manual navigation, and dot indicators — all implemented with pure front-end code.

🚀 Features

🖼️ Dynamic image carousel with smooth transitions

⏱️ Automatic slide change every few seconds

🔘 Clickable dot indicators for navigation

⬅️➡️ Manual previous/next buttons

📱 Responsive layout for all screen sizes

🎨 Modern design with fade and slide animations

🧰 Tech Stack
Technology	Description
HTML5	Structure of the slider
CSS3	Styling and animation
JavaScript (ES6)	Logic for dynamic image transitions
📂 Project Structure
📁 dynamic-image-slider
 ┣ 📜 index.html
 ┣ 📜 README.md
 ┗ 📂 assets/
     ┗ 📜 (optional images or icons)

⚙️ How to Run

Clone the repository

git clone https://github.com/your-username/dynamic-image-slider.git
cd dynamic-image-slider


Open the project

Simply open the index.html file in your web browser.

OR, if you’re using VS Code:

Install the extension Live Server

Right-click on index.html

Choose Open with Live Server

🖼️ Screenshots
<img width="1122" height="684" alt="image" src="https://github.com/user-attachments/assets/cbe08d00-44e7-46b4-8068-1788084bb137" />


	
💡 Working Principle

All images are placed inside a container using Flexbox.

JavaScript dynamically moves the image container using the CSS property:

transform: translateX(-index * 100%);


Automatic sliding is achieved using:

setInterval(() => { /* next slide logic */ }, 3000);


Dots are generated dynamically based on the number of images.

🔧 Customization

You can easily customize:

Image URLs → inside the <img> tags in HTML

Slide Interval → change the time (3000 ms) in setInterval()

Transition Speed → edit transition time in CSS

🌟 Future Enhancements

Add fade animation or 3D transitions

Include image captions or titles

Pause autoplay on hover

Load images dynamically using an API

👩‍💻 Author

[Alagu raja M]
🔗 GitHub Profile

📧 yourname@email.com
