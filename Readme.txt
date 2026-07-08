# Personal Portfolio Website Template

A beautiful, professional, responsive, and animated single-page resume and portfolio website template.

---

## 🛠️ Tech Stack & Dependencies

### Frontend / Presentation Layer
*   **HTML5 & CSS3:** Structure and responsive styling (custom rules in assets/css/style.css).
*   **Bootstrap v5.3.2:** Responsive CSS grid framework.
*   **Google Fonts:** Open Sans, Raleway, Poppins.
*   **Custom JavaScript:** Scroll logic, sections display, mobile menu, and initialization (assets/js/main.js).

### Third-Party Assets & Plugins (under assets/vendor/)
*   **Swiper:** Responsive testimonials and portfolio details sliders.
*   **GLightbox:** Lightbox library for viewing images/videos in modals.
*   **Isotope Layout:** Interactive filtering and sorting for portfolio items.
*   **PureCounter:** Numerical counter animations.
*   **Waypoints:** Triggering animations on scroll.
*   **Icons:** Bootstrap Icons, Boxicons, and Remixicon.

### Backend Layer
*   **PHP:** Handles AJAX contact form submission (forms/contact.php).
*   **Validation Client:** Client-side validator (assets/vendor/php-email-form/validate.js).

---

## 📬 Contact Form Configuration

We have implemented a native PHP mail() fallback function in forms/contact.php. 
To use this contact form:
1. Open forms/contact.php.
2. Find the line: $receiving_email_address = 'contact@example.com';
3. Replace 'contact@example.com' with your actual receiving email address.
4. Ensure your server environment supports standard PHP mail configuration.

---

## 📂 Project Structure

*   index.html - The main single-page website.
*   portfolio-details.html - Sample detailed view for portfolio items.
*   forms/ - Contact form submission backend.
*   assets/ - CSS styles, images, JavaScript, and third-party vendors.

---

## 📄 Copyright & License

© 2026 Anuj Singh Rajput. All Rights Reserved.

This project, including its source code, design, documentation, features, and related materials, was developed by Anuj Singh Rajput for educational and portfolio purposes.

Unauthorized copying, reproduction, modification, distribution, publication, or commercial use of this project, in whole or in part, is not permitted without prior written permission from the copyright owner.

You may view and study this project for educational and learning purposes. Any reuse, modification, distribution, or commercial use requires explicit permission from the author.

*   **Developer:** Anuj Singh Rajput
*   **Project:** MY Portfolio
