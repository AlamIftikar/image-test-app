# Image Gallery Demo (Dark Theme)

Summary
- A small static HTML page that displays two embedded images side-by-side under the heading "My Image Gallery" on a dark background. Images are loaded via base64-encoded data URIs.

Key features
- Dark page background to create a high-contrast look
- Heading above the images: "My Image Gallery"
- Images displayed side-by-side with spacing between them
- White image cards on a dark background for readability
- Responsive layout: side-by-side on larger screens, stacked on small screens
- No external dependencies (static HTML, CSS, and inline images)

Setup instructions
- Save the file as index.html
- No server is required; open directly in a web browser

Usage instructions
- Open index.html in your browser to view the gallery
- The images are embedded via data URIs; no network requests are needed

Technical details
- HTML structure:
  - A container div with a white card look sits on a dark body background
  - A heading (h2) labeled "My Image Gallery" above a .gallery div
  - The .gallery uses CSS flexbox to arrange two images side-by-side with a gap
- CSS structure:
  - :root defines color tokens
  - body uses a dark background (#0b0f14) and light text
  - .container creates a white card with padding and rounded corners
  - .gallery uses display: flex with gap for spacing
  - Responsive behavior via a media query to stack images on small screens
- JavaScript:
  - Not required for this static layout; a placeholder script is included

Changes made in Round 2
- Added a new heading above the images: "My Image Gallery"
- Converted the image layout to a side-by-side gallery using CSS flexbox
- Introduced a dark background for the page and a white content card for contrast
- Improved responsiveness to stack images on small screens
- Removed inline paragraph blocks around images to fit the new layout

Deployment info (GitHub Pages)
- Create a new GitHub repository
- Push index.html (and optional README) to the repository
- Enable GitHub Pages (Settings > Pages) and select the main branch (root) as the source
- Access the site at https://<your-username>.github.io/<repository-name>/

License
- MIT License

This project is ready to deploy on GitHub Pages and showcases a clean, responsive image gallery with a dark theme.