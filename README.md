# Dibyadyuti's Portfolio Website Documentation

This documentation provides a comprehensive overview of the **Dibyadyuti's Portfolio Website**, detailing the features, structure, and technologies used in the development of the website.

---

## Table of Contents

- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Website Structure](#website-structure)
- [Usage](#usage)
- [Form Handling with Firebase](#form-handling-with-firebase)
- [Conclusion](#conclusion)

---

## Overview

This portfolio website showcases **Dibyadyuti Dutta**, a Computer Science Engineering student with a passion for coding, web development, AI, cybersecurity, and more. The website presents a professional profile, highlighting skills, education, projects, and contact information. The design is simple, interactive, and fully responsive.

---

## Technologies Used

### Frontend
- **HTML5:** Used for the structure and content of the website.
- **CSS3:** Styling for layout, fonts, and design elements.
- **JavaScript:** Adds interactivity, form validation, dark mode functionality, and Firebase interaction.
- **Firebase:** Handles form submissions and stores feedback in Firestore.

### Libraries
- **Google Fonts:** Custom font for better typography.
- **Font Awesome:** Used for icons and UI enhancements.

---

## Website Structure

The website is organized into several main sections, each addressing a different aspect of the portfolio:

1. **Header:**
   - Contains the navigation bar with links to different sections.
   - Includes the dark mode toggle and a logo image.

2. **About Me:**
   - An introductory paragraph describing Dibyadyuti’s background and areas of expertise.

3. **Connect with Me:**
   - Displays social media links and an email address to allow users to connect with Dibyadyuti.

4. **Skills:**
   - Lists skills related to programming, web development, and database management.

5. **Tech Stack:**
   - Features progress bars to represent proficiency in various technologies.

6. **Education:**
   - Lists Dibyadyuti’s educational background, including the current degree and previous schooling.

7. **Projects:**
   - Showcases Dibyadyuti’s key projects with a description and links to GitHub repositories.

8. **Certificates:**
   - Displays a list of Dibyadyuti’s certifications.

9. **Contact:**
   - Contains a form where users can send messages to Dibyadyuti. The form integrates with Firebase Firestore to store feedback.

---

## Usage

To use the website, open the **HTML file** in any modern browser. The website is responsive, adjusting to various screen sizes for both desktop and mobile devices.

### Dark Mode Toggle
- Users can toggle between light and dark themes using the **moon icon** in the navigation bar. This adjusts the color scheme for better visibility in low-light environments.

### Contact Form Submission
- Users can fill out the contact form, which includes fields for **name**, **email**, and **comment**. Upon submission, the data is sent to Firebase Firestore, and a success alert appears. The form includes basic validation to ensure that all fields are filled before submission.

---

## Form Handling with Firebase

The **Contact Form** is integrated with Firebase to store submitted data. Here’s how it works:

1. **Firebase Initialization:**
   - The Firebase SDK is initialized with the web app's configuration. This configuration links the website to the Firebase project where feedback will be stored.

2. **Form Submission:**
   - When the user submits the contact form, the form fields (name, email, comment) are collected.
   - The form data is then sent to Firebase Firestore and stored in a **feedbacks** collection.

3. **Success & Error Handling:**
   - After the form is successfully submitted, a success notification appears to inform the user that their feedback was sent.
   - If there’s an issue with the submission (e.g., network failure), the user is notified with an error message.

---

## Conclusion

This portfolio website is designed to present **Dibyadyuti Dutta’s** skills, education, and projects in a clean and professional manner. The integration with Firebase for feedback storage and the use of modern web technologies ensure that the website is both functional and interactive.

By following best practices in web development, this portfolio serves as an excellent representation of Dibyadyuti’s capabilities in front-end development, backend integration (Firebase), and web design. It is built to be accessible, interactive, and visually appealing for all visitors.

---

Feel free to explore the website by visiting the live version or by cloning the repository. Any feedback or inquiries can be submitted through the **Contact** section.
