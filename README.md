##Netflix Clone
A visually appealing and responsive clone of the Netflix landing page, built using modern web technologies. This project replicates the core layout, including the hero section, movie carousels, feature cards, and an interactive FAQ section.

🚀 #Features
Responsive Hero Section: Includes a dynamic background with a dark overlay, navigation bar, and a membership call-to-action.

Language Selection: A styled dropdown menu to toggle between different languages (UI representation).

Trending Now Carousel: A horizontal scrolling section featuring movie posters with rank numbering.

Interactive FAQ: An accordion-style "Frequently Asked Questions" section where users can toggle answers.

Feature Highlights: Modern cards detailing Netflix benefits like "Enjoy on your TV" and "Watch everywhere," styled with custom SVG icons.

Custom Styling: Uses CSS gradients, radial overlays, and curved boundary lines to mimic the authentic Netflix aesthetic.

🛠️ #Tech Stack
HTML5: Semantic structure for the landing page.

CSS3: Custom styling, flexbox layouts, and responsive design.

JavaScript: Vanilla JS for handling interactive elements like the FAQ accordion.

Google Fonts: Utilizes "Noto Sans" and "Martel Sans" for consistent typography.

📂 #Project Structure
Plaintext

.
├── index.html      # Main project structure and content
├── index.css       # Custom styling and layout rules
├── logo.svg        # Netflix logo (required asset)
├── arrow.svg       # UI icon (required asset)
└── ...             # Other SVG icons and assets


📝 #JavaScript Logic
The project includes a lightweight script to manage UI interactions:

FAQ Toggle: Uses querySelectorAll to listen for clicks on questions and toggles the display property of the corresponding answer div.

🎨 #Design Details
Hero Background: A high-resolution perspective image from Netflix's CDN with a custom radial gradient overlay.

Curved Borders: Implemented using border-radius: 60%/100px 100px 0 0 and linear gradients to create the signature section separators.
