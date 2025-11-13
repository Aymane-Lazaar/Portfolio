# 👨‍💻 Personal Portfolio Website

A fully responsive, modern, and interactive personal portfolio website built to showcase skills, projects, and professional experience. The site features a dynamic theme switcher, light/dark mode, and a functional contact form.

![Project Screenshot](./assets/img/project1.jpeg)
*(Note: Replace the image path above with a screenshot of your actual website homepage)*

## ✨ Features

* **🎨 Dynamic Theme Switcher:** Users can choose from 5 different color accents.
* **🌓 Light & Dark Mode:** Fully supported theme toggling for better user experience.
* **📱 Fully Responsive:** Optimized for mobile, tablet, and desktop devices using CSS Media Queries.
* **📂 Filterable Portfolio:** Projects can be filtered by category (Development, Design, etc.) using **MixItUp**.
* **📜 Smooth Animations:** Interactive UI with hover effects and smooth transitions.
* **🛠️ Services Carousel:** a touch-friendly slider using **Swiper.js**.
* **📝 Accordion Resume:** Expandable sections for Education and Experience.
* **📧 Functional Contact Form:** Integrated with **EmailJS** to send messages directly to your email without a backend server.

## 🛠️ Technologies Used

* **HTML5** - Semantic markup.
* **CSS3** - Custom properties (variables), Flexbox, Grid, and animations.
* **JavaScript (ES6+)** - DOM manipulation and logic.
* **Libraries:**
    * [Swiper.js](https://swiperjs.com/) (Sliders)
    * [MixItUp](https://www.kunkalabs.com/mixitup/) (Filtering)
    * [EmailJS](https://www.emailjs.com/) (Contact Form)
    * [Remix Icons](https://remixicon.com/) (Icons)
    * [Google Fonts](https://fonts.google.com/) (Typography)


## ⚙️ Configuration

### EmailJS Setup
To make the contact form work for **your** email address, you need to update the IDs in `assets/js/main.js`:

1.  Create an account at [EmailJS](https://www.emailjs.com/).
2.  Create a **Service** and a **Template**.
3.  Open `assets/js/main.js` and find the `sendEmail` function.
4.  Replace the keys with your own:

```javascript
emailjs.sendForm(
    'YOUR_SERVICE_ID',   // e.g., service_xxxx
    'YOUR_TEMPLATE_ID',  // e.g., template_xxxx
    '#contact-form',
    'YOUR_PUBLIC_KEY'    // e.g., sjIDwgxxxxxx
)
```

💿 How to Run Locally

git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
