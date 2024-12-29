# Dibyadyuti's Portfolio Website Documentation

This documentation provides a comprehensive overview of the **Dibyadyuti's Portfolio Website**, detailing the features, structure, and technologies used in the development of the website.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Website Structure](#website-structure)
- [Usage](#usage)
- [Form Handling with Firebase](#form-handling-with-firebase)
- [Conclusion](#conclusion)

---

## Overview

This portfolio website showcases **Dibyadyuti Dutta**, a Computer Science Engineering student passionate about coding, web development, AI, cybersecurity, and more. The website presents a professional profile, including a description of his skills, education, projects, and contact information. The website is designed to be simple, interactive, and fully responsive.

---

## Features

The website includes the following main features:

1. **Navigation Bar:**
   - Contains links to various sections: Home, About Me, Projects, Contact, and a Resume download link.
   - A dark mode toggle allows users to switch between light and dark themes.

2. **About Me Section:**
   - Displays a profile picture and an introductory paragraph with details about Dibyadyuti’s background, skills, and interests.

3. **Connect with Me Section:**
   - Contains social media links for easy connection.
   
4. **Skills Section:**
   - A list of programming and development skills with visual representation using a simple list.

5. **Tech Stack Section:**
   - Shows the proficiency of Dibyadyuti in different technologies using progress bars.

6. **Education Section:**
   - Lists the educational background, including the ongoing degree and previous schooling.

7. **Projects Section:**
   - Showcases key projects with clickable links that redirect to GitHub repositories.

8. **Contact Form:**
   - Allows users to send feedback or contact Dibyadyuti directly. The form integrates with Firebase to store the feedback.

---

## Technologies Used

### Frontend
- **HTML5:** Structure and content of the website.
- **CSS3:** Styling the layout, fonts, and design elements.
- **JavaScript:** Adds interactivity, form validation, dark mode functionality, and Firebase interaction.
- **Font Awesome:** Provides icons.
- **Firebase:** Handles form submissions and stores feedback data in Firestore.

### Libraries
- **Google Fonts (Poppins):** Custom font for better typography.
- **Font Awesome:** Used for icons.
  
---

## Website Structure

The website is organized into several main sections, with each section addressing a different aspect of the portfolio:

### 1. **Header:**
   - Contains the navigation bar with links to different sections.
   - Includes a dark mode toggle and the logo image.
   - The header also includes a profile picture of Dibyadyuti and a brief description in the **About Me** section.

### 2. **About Me:**
   - An introductory paragraph describing Dibyadyuti’s background, interests, and areas of expertise.
   
### 3. **Connect with Me:**
   - Provides users with links to Dibyadyuti’s social media accounts and email.
   
### 4. **Skills:**
   - Displays a list of skills like programming, web development, and database management.

### 5. **Tech Stack:**
   - Features a set of progress bars representing proficiency in various programming languages and tools.

### 6. **Education:**
   - Lists the educational background, including current and past institutions.

### 7. **Projects:**
   - Highlights key projects developed by Dibyadyuti, each with a brief description and a link to the GitHub repository for further details.

### 8. **Contact:**
   - Contains a form to allow users to contact Dibyadyuti directly. The form interacts with Firebase Firestore to save user feedback.


---

## Usage

To use the website, simply open the **HTML file** in any modern browser. The website is fully responsive and adapts to various screen sizes, making it accessible on both desktop and mobile devices.

### Dark Mode Toggle
- Users can toggle between light and dark themes using the **moon icon** in the navigation bar. This adjusts the overall website's color scheme for better visibility in low-light environments.

### Contact Form Submission
- Users can fill out the contact form, which includes fields for **name**, **email**, and **comment**. Upon submission, the data is sent to Firebase Firestore, and a success alert appears. The form is validated to ensure all fields are filled before submission.

---

## Form Handling with Firebase

The **Contact Form** is integrated with Firebase to store submitted data. Here’s how it works:

1. **Firebase Initialization:**
   - The Firebase SDK is initialized with the web app's configuration (provided in the `firebaseConfig` object). This configuration links the website to the Firebase project where feedback will be stored.

2. **Form Submission:**
   - When the user submits the contact form, the values (name, email, comment) are collected.
   - If the fields are filled out correctly, the data is added to the Firestore database in a **feedbacks** collection.

3. **Success & Error Handling:**
   - After the form is successfully submitted, the user is notified with an **alert** that their feedback was successfully sent.
   - If there is an issue with the form submission (e.g., network failure), the user is alerted with an error message.

---

## Conclusion

This portfolio website provides a clean, simple, and professional way to showcase **Dibyadyuti Dutta’s** skills, education, and projects. The integration with Firebase for feedback storage and the use of modern web technologies ensures that the website is both functional and interactive.

By following best practices in web development, this portfolio serves as an excellent representation of Dibyadyuti's capabilities in front-end development, backend integration (Firebase), and design. It is designed to be accessible, interactive, and visually appealing to anyone who visits.

---

Feel free to explore the website by visiting the live version or by cloning the repository. Any feedback or inquiries can be submitted through the **Contact** section.
