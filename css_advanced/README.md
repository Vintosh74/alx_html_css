Homepage Design Project
This project implements a modern homepage design, focusing on advanced CSS layouts and styling, based on a provided Figma design. The goal is to replicate the visual aesthetics and responsiveness specified in the design.

Features
Responsive Header: A dynamic header with a logo and navigation links.

Hero Section: A prominent banner with a main title, a catchy phrase, and a call-to-action button.

Team Showcase: A section introducing team members with their photos, names, and roles.

Inspirational Quote: A dedicated section to highlight a powerful quote with an author's image and details.

Featured Videos: A grid displaying video cards with thumbnails, titles, descriptions, authors, and ratings.

Membership Plans: A section outlining various membership tiers with images, titles, descriptions, and action buttons.

Frequently Asked Questions (FAQ): A structured section for common questions and answers.

Footer: A clean footer with a logo, social media links, and copyright text.

Technologies Used
HTML5: For structuring the web content.

CSS3: For styling and layout, including advanced techniques for responsiveness.

Figma: The design tool used to create the visual mockups.

Setup and Usage
To view this project locally:

Clone the repository:

git clone <your-repository-url>

(Replace <your-repository-url> with the actual URL of your GitHub repository.)

Navigate to the project directory:

cd html_advanced_layout_project

Open index.html: Simply open the index.html file in your web browser.

Important: Images and Fonts
This project relies on specific images and custom fonts to match the Figma design.

Images: The index.html currently uses placehold.co URLs for placeholder images. For the complete design, you will need to download the actual images from the provided Figma link's assets and place them in an images/ directory within your project structure. Update the src attributes in index.html accordingly.

Example image paths expected:

images/logo.png

images/team-member-1.jpg, images/team-member-2.jpg, etc.

images/video-thumbnail-1.jpg, etc.

images/membership-plan-basic.jpg, etc.

images/social-facebook.png, images/social-twitter.png, images/social-instagram.png

Fonts:

Source Sans Pro: This font is linked directly from Google Fonts in index.html.

Spin Cycle OT: This is a custom font. Ensure you download the font files (e.g., .ttf, .woff, .woff2) and place them in a fonts/ directory. The styles.css file contains @font-face rules assuming this path.

Design Source
The design for this project is available on Figma. You can access and duplicate the design to your drafts to inspect all design details (colors, typography, spacing, etc.) here:

Figma Design Link

Note on Values: Some values in Figma might be in floats. These have been rounded to the nearest reasonable integer or a consistent decimal place in the CSS for simplicity and consistency.
