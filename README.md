# Aakash Digital Photo Studio - Website

This repository contains the source code for the Aakash Digital Photo Studio website. It's a single-page, responsive website designed to showcase the studio's services, portfolio, and contact information.

## Features

*   **Responsive Design:** Adapts to various screen sizes (desktops, tablets, and mobile phones).
*   **Smooth Scrolling Navigation:** Easy navigation between sections (Home, About, Services, Works, Contact).
*   **Preloader Animation:** Displays a loading animation while page assets are being loaded.
*   **Home Section:** A welcoming hero section with the studio name and tagline.
*   **About Us Section:** Provides information about the studio, along with statistics like "Projects Done," "Happy Clients," and "Shoots."
*   **Services Section:** Showcases the different types of photography services offered (e.g., Wedding, Portrait, Fashion) with image previews.
*   **Works Section (Portfolio):** A gallery displaying examples of the studio's work. Images open in a lightbox for a better viewing experience.
*   **Contact Us Section:** Includes a contact form, physical address with a Google Maps link, phone number, and an "Send Email" button.
*   **Social Media Links:** Direct links to the studio's/owner's Facebook and YouTube profiles.
*   **Lightbox Gallery:** For viewing portfolio images in a larger, focused overlay.
*   **Developer Credits:** In the footer, crediting the website developer.

## Technologies Used

*   **HTML5:** For the structure and content of the website.
*   **CSS3:** For styling and layout, including responsive design elements. (Linked via `css/style.css`)
*   **JavaScript:** For interactive elements like the navigation toggle, preloader, and lightbox. (Linked via `js/main.js`)
*   **jQuery:** A JavaScript library used to simplify DOM manipulation and event handling. (Linked via `js/jquery.min.js`)

## File Structure
Use code with caution.
Markdown
.
├── aakshlogo.png # Studio logo used in the header
├── index.html # The main HTML file for the website
├── css/
│ └── style.css # Main stylesheet
├── js/
│ ├── main.js # Custom JavaScript for site functionality
│ └── jquery.min.js # jQuery library
├── img/
│ ├── about.jpg # Image for the About Us section
│ ├── icons/ # Folder for SVG and PNG icons
│ │ ├── arrow-down.svg
│ │ ├── facebook.svg
│ │ ├── favicon.ico # Website favicon
│ │ ├── next.svg
│ │ ├── prev.svg
│ │ └── youtube.png
│ ├── service/ # Images for the Services section
│ │ ├── 1.jpg
│ │ ├── ... (up to 6.jpg)
│ └── works/
│ ├── large/ # Large versions of portfolio images (for lightbox)
│ │ ├── 1.jpg
│ │ └── ... (up to 6.jpg)
│ └── thumb/ # Thumbnail versions of portfolio images
│ ├── 1.jpg
│ └── ... (up to 6.jpg)
└── README.md # This file
## Setup and Usage

1.  **Clone the repository (optional):**
    ```bash
    git clone <repository-url>
    cd <repository-folder>
    ```
2.  **Open in Browser:**
    Simply open the `index.html` file in your preferred web browser.

No special build steps or server-side requirements are needed as this is a static HTML, CSS, and JavaScript website.

## Website Sections

*   **Preloader:** A visual loader displayed while the page content is loading.
*   **Header:** Contains the studio logo and navigation menu. The menu is toggleable on smaller screens.
*   **Home Section:** Full-screen introductory section with the studio's name and a tagline. Includes a scroll-down arrow.
*   **About Section:** Details about the studio, an image, and key statistics (Projects Done, Happy Clients, Shoots). Includes a "Contact Us" button.
*   **Service Section:** Grid layout showcasing various photography services offered, with images and overlay titles.
*   **Work Section:** A portfolio gallery of the studio's work. Images have thumbnails and larger versions for the lightbox.
*   **Contact Section:** Provides a contact form (Name, Email/Phone, Message), address, phone number, an "Send Email" button, and social media links.
    *   The `sendEmail()` function for the "Send Email" button would need to be implemented in `js/main.js` (e.g., using `mailto:`).
    *   The contact form is currently front-end only. For it to send messages, backend integration or a service like Formspree/Netlify Forms would be required.
*   **Lightbox:** A modal pop-up for viewing portfolio images, with navigation (previous/next) and a close button.
*   **Footer:** Contains copyright information and a link to the developer's website.

## Customization

*   **Content:** Modify the text, titles, and image `src` attributes directly in `index.html`.
*   **Images:** Replace images in the `img/` subdirectories. Ensure new image paths are correctly updated in `index.html`.
*   **Styling:** Adjust the visual appearance by editing `css/style.css`.
*   **Functionality:** Modify or extend interactive features in `js/main.js`.
*   **Contact Form Backend:** To make the contact form functional, you'll need to add backend processing or integrate a third-party form submission service.
*   **Email Button:** Implement the `sendEmail()` JavaScript function in `js/main.js`. A simple implementation could be:
    ```javascript
    // In js/main.js
    function sendEmail() {
      window.location.href = "mailto:yourstudioemail@example.com?subject=Inquiry from Website";
    }
    ```
    Replace `yourstudioemail@example.com` with the actual studio email address.

## Credits

*   **Website Design and HTML Structure:** Based on the provided HTML.
*   **Developer Credit (as per footer):** Yubraj Dhakal Upamanyu.

---

This README should provide a good overview of your project. You can save this content as `README.md` in the root directory of your project.
Use code with caution.
