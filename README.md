# Personal Portfolio

A static, modern, and professional personal portfolio website. Designed and developed to be easily hosted on **GitHub Pages**.

## Features
- **Responsive Design**: Looks great on desktop, tablet, and mobile displays.
- **Dark/Light Mode**: Default dark mode with an elegant toggle button (saves preference via LocalStorage).
- **Smooth Animations**: Clean scroll reveal animations and hover transitions.
- **No Backend**: Built with pure HTML5, CSS3, and Vanilla JavaScript.
- **Ready for GitHub Pages**: All paths are relative, ready to be deployed out of the box.

## Structure
- `index.html`: The main single-page structure containing all sections.
- `css/style.css`: Contains all styling, custom properties (CSS variables), and responsive media queries.
- `js/script.js`: Handles theme toggling, mobile menu interaction, active nav links, and scroll animations.
- `assets/images/`: Directory to store your profile photo and project screenshots.
- `assets/documents/`: Directory to store your CV/Resume in PDF or DOCX format.

## How to Customize
1. Open `index.html` and replace all template placeholders (`[NAMA]`, `[EMAIL]`, `[GITHUB]`, `[LINKEDIN]`, `[FOTO]`, `[CV]`).
2. **Profile Photo**: Add your photo to the `assets/images/` directory and replace the `<div class="photo-placeholder">...</div>` with an `<img>` tag (e.g. `<img src="assets/images/profile.jpg" alt="Profile">`). Update CSS if needed for the image to fit beautifully inside the circle wrapper.
3. **Resume/CV**: Add your CV to the `assets/documents/` directory and update the `href="assets/documents/[CV]"` link in the About section.
4. Modify the `Skills`, `Experience`, `Education`, and `Projects` sections with your actual professional data.

## Deployment to GitHub Pages
1. Push this repository to a new repository on your GitHub account.
2. Go to your repository **Settings**.
3. Navigate to **Pages** on the left sidebar.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` or `master` branch and the `/ (root)` folder.
6. Click **Save**. Your site will be live and accessible shortly!
