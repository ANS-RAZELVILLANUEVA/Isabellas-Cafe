# Project Title: Design and Development of an Interactive Website for Isabella’s Café, Bay Walk, Marina Street, San Jose de Buenavista, Antique

## Designer: Razel Mae S. Villanueva BSIT-3A

## Short Overview of the Project
The Interactive Website for Isabella’s Café located at Bay Walk, Marina Street, San Jose de Buenavista, Antique is designed as a promotional platform that highlights the café’s location, ambiance, and offerings. The website showcases the café’s aesthetically pleasing interior and exterior designs to give visitors a glimpse of its relaxing atmosphere. It also features the café’s delicious drinks and pastries, allowing potential customers to explore its menu and encouraging them to visit the café.

## Framework Used
*   **HTML5 / CSS3 / Vanilla JavaScript**: Core building blocks of the website.
*   **Tailwind CSS (via CDN)**: Primary CSS framework used for utility-first styling, responsive design layouts, and custom animations.
*   **FontAwesome (v6.4.0)**: Used for UI icons (social media, UI navigation, contact details).
*   **SweetAlert2**: Used for modern, responsive, and customizable popup alerts on the contact form.
*   **Google Fonts**: Integrated the 'Poppins' typeface for a modern and clean typography style.

## URL/Domain
https://ans-razelvillanueva.github.io/Isabellas-Cafe/

---

## Note on the Use of Artificial Intelligence
In the creation and development of this website, I heavily relied on Google AI Studio to assist with complex programming tasks such as fixing intricate UI designs, structuring responsive layouts, debugging JavaScript functionalities, conceptualizing ideas into tangible visual designs, and realigning dislocated UI elements across different screen sizes, while simultaneously utilizing Google Gemini for constructing coherent sentences, generating engaging paragraphs, and ensuring impeccable grammar throughout the site's textual content.

---

## Use of AI Tool

**1. How it is used:** Configuring custom design tokens in Tailwind CSS
*   **Prompt:** "Write a Tailwind CSS configuration script using the CDN approach to include custom colors (like a specific gold), custom fonts (Poppins), and custom keyframe animations for a continuous gradient text effect and floating images."
*   **How it was applied:** The generated script was placed in the `<head>` of all HTML files, establishing the foundational design system (like `bg-gradient-gold`, `animate-gradient`, and custom zinc colors) used uniformly across the website.

**2. How it is used:** Creating a dynamic, scroll-responsive Navbar
*   **Prompt:** "Create a JavaScript function for a fixed navigation bar that changes its theme (from transparent/dark text to solid white/black text) depending on the background color of the section it is currently scrolling over. Use `data-theme` attributes on sections."
*   **How it was applied:** Implemented the `handleNavTheme` JavaScript function across all pages, allowing the navbar to seamlessly adapt its text color and background blur as the user scrolls past dark hero sections into light content sections.

**3. How it is used:** Building a scroll-reveal animation system
*   **Prompt:** "Write a lightweight Vanilla JavaScript function and corresponding CSS classes to make HTML elements slide up and fade in seamlessly as they enter the browser's viewport during scrolling."
*   **How it was applied:** The `.reveal` and `.active` CSS classes, paired with the `reveal()` event listener, were applied to text blocks, images, and grids across all pages to create a highly interactive and smooth browsing experience.

**4. How it is used:** Generating website copywriting (About Us)
*   **Prompt:** "Act as a professional copywriter. Write engaging, descriptive paragraphs for a beachfront cafe named Isabella's Cafe in Antique. Highlight the sunset view, open-air architecture, and aesthetic black-and-gold design. Keep it inviting and elegant."
*   **How it was applied:** Used Google Gemini's output to populate the text content in the `about.html` page, specifically under "The Visionaries" and "A Front Row Seat to the Sunset" sections.

**5. How it is used:** Developing a 3D Coverflow Carousel for the Gallery
*   **Prompt:** "Create a 3D coverflow image carousel using HTML, CSS, and Vanilla JavaScript. The active image should be centered and large, while the images on the left and right should be scaled down, pushed back in 3D space, and darkened. It needs to auto-rotate every 2 seconds."
*   **How it was applied:** The code was integrated into the "Featured Photos" section of `gallery.html`, creating a highly dynamic, visually appealing 3D slider for the cafe's top photographs.

**6. How it is used:** Structuring a dynamic filtering system for the Menu
*   **Prompt:** "Write a JavaScript logic for a menu page that filters items based on a dropdown category selection and a text search bar. Elements should fade out and fade in using CSS animations when filtered."
*   **How it was applied:** Applied in `menu.html` to allow users to search for specific cravings or filter by categories like "Coffee," "Matcha," or "Meals," making the extensive menu easy to navigate.

**7. How it is used:** Designing a Masonry layout for the photo gallery
*   **Prompt:** "How can I create a responsive masonry image grid using only CSS column-count in Tailwind CSS? Ensure the items don't break across columns."
*   **How it was applied:** Used the provided CSS (`column-count`, `break-inside: avoid`) in `gallery.html` to display the "All Photos" section in a Pinterest-style masonry grid that adapts to mobile, tablet, and desktop screens.

**8. How it is used:** Implementing infinite auto-scrolling carousels
*   **Prompt:** "Create a smooth, infinitely auto-scrolling horizontal carousel using Vanilla JS. It should pause when hovered and allow manual scrolling via buttons or touch swipe."
*   **How it was applied:** Implemented in `home.html` (Popular Selections) and `gallery.html` (Recent Captures) to constantly cycle through food/drink items and photos without user intervention.

**9. How it is used:** Creating an interactive Lightbox / Modal for images
*   **Prompt:** "Write a JavaScript-based modal/lightbox that opens when an image card is clicked. It should darken the background, display the image in full size in the center, and include a close button. Prevent the body from scrolling when open."
*   **How it was applied:** Added to both `menu.html` (to show product details and prices) and `gallery.html` (to view high-resolution photos), enhancing the user interaction without navigating away from the page.

**10. How it is used:** Building a cross-fading Review/Testimonial slider
*   **Prompt:** "Create a JavaScript function that cycles through different sets of customer reviews. It should hide the current grid of 3 reviews and fade in the next grid of 3 reviews every 6 seconds."
*   **How it was applied:** Applied to the "What Our Guests Say" section in `home.html`, allowing the website to display multiple customer feedbacks dynamically within a limited vertical space.

**11. How it is used:** Enhancing the Contact Form with SweetAlert2
*   **Prompt:** "How do I integrate SweetAlert2 into a standard HTML form submission? I want a customized success popup with a customized button that matches a gold-and-black theme, and the form should reset after clicking done."
*   **How it was applied:** Used the generated JavaScript snippet in `contact.html` to intercept the form submission and display a beautiful, themed success modal to the user instead of a basic browser alert.

**12. How it is used:** Styling an interactive Google Maps iframe
*   **Prompt:** "Design a container for a Google Maps iframe using Tailwind CSS. It should have a gradient gold border, apply a grayscale filter to the map by default, and return to full color when hovered."
*   **How it was applied:** Implemented in the `contact.html` page to make the standard map embed match the premium aesthetic of the café's branding.

**13. How it is used:** Implementing smooth page transitions
*   **Prompt:** "Provide CSS and JavaScript to create a smooth fade-in and fade-out page transition effect when clicking links to navigate between different HTML pages."
*   **How it was applied:** Applied in `about.html` (and easily adaptable to others) utilizing the `.page-transitioning` class to make page loads feel like a modern Single Page Application (SPA).

**14. How it is used:** Generating copywriting for Menu item descriptions
*   **Prompt:** "Write short, appetizing descriptions (1-2 sentences max) for cafe menu items: Spanish Latte, Chicken Parmigiana, Pink Milk, and Ube Halo-Halo Frappe."
*   **How it was applied:** Utilized Google Gemini's mouth-watering descriptions to populate the text cards in the "Guest Favorites" section on `menu.html` and the carousel on `home.html`.

**15. How it is used:** Debugging Z-index overlapping issues
*   **Prompt:** "My fixed navbar is showing up underneath my image modal when the modal opens. How do I fix CSS z-index stacking context issues using Tailwind classes?"
*   **How it was applied:** Followed Google AI Studio's advice to strictly manage z-indexes (`z-50` for navbar, `z-[100]` for modals) across the site, ensuring popup elements always appear on top of fixed navigational elements.

**16. How it is used:** Hiding scrollbars while maintaining functionality
*   **Prompt:** "How can I hide the horizontal scrollbar in a CSS flexbox container while still allowing the user to scroll left and right using swipe or a mouse wheel?"
*   **How it was applied:** Used the generated `.hide-scrollbar` custom CSS rules applied to the horizontal carousels in `home.html` and `gallery.html` for a cleaner UI design.

**17. How it is used:** Designing complex Hero sections with overlays
*   **Prompt:** "Create a Tailwind CSS hero section with a background image, a black gradient overlay to make text readable, and floating text animations. The text should have a gold gradient fill."
*   **How it was applied:** Applied to the main headers of `home.html`, `menu.html`, and `gallery.html`, establishing a strong, visually striking first impression for website visitors.

**18. How it is used:** Structuring a data-driven Menu layout
*   **Prompt:** "How can I store a list of 30+ menu items (coffee, meals, add-ons) in a JavaScript array and dynamically render them as HTML cards into a grid using a loop?"
*   **How it was applied:** Implemented in `menu.html`, allowing the menu to be easily updated by editing a JavaScript array (`menuData`) rather than manually hardcoding dozens of individual HTML div blocks.

**19. How it is used:** Designing responsive, modern footers
*   **Prompt:** "Design a modern footer using Tailwind CSS. It should have a dark theme, a top border with a gold gradient, a logo section, quick links, contact info with icons, and business hours."
*   **How it was applied:** The AI-generated structure was used as the standard footer across all HTML pages, providing a consistent and professional conclusion to the bottom of every page.

**20. How it is used:** Creating Custom animated buttons
*   **Prompt:** "Create a custom CSS class for a button that has a shiny gold gradient background. When hovered, the gradient should slide horizontally, the button should lift up slightly, and it should cast a gold drop shadow."
*   **How it was applied:** The `.btn-gold` custom CSS class was generated and applied to primary Call-to-Action buttons site-wide (e.g., "See Menu", "Send Message", "Explore Gallery") to drive user engagement.
