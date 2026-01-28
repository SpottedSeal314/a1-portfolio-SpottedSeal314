# Max Richardson's Portfolio

This is my professional portfolio website showcasing my work and experience.

## GitHub Pages Setup

This repository is configured to automatically deploy to GitHub Pages using GitHub Actions.

### Setup Instructions:
To enable GitHub Pages for this repository, follow these steps:

1. **Go to Repository Settings**:
   - Navigate to your repository on GitHub
   - Click on "Settings" tab at the top

2. **Enable GitHub Pages**:
   - In the left sidebar, click on "Pages" under "Code and automation"
   - Under "Source", select "GitHub Actions"
   - This allows the workflow to deploy the site

3. **The workflow will automatically deploy** when:
   - Code is pushed to the `main` or `copilot/connect-repo-using-github-pages` branches
   - You can also manually trigger it from the "Actions" tab

4. **Access Your Site**:
   - After deployment, your site will be available at:
   - `https://spottedseal314.github.io/a1-portfolio-SpottedSeal314/`

### How it works:
- The workflow is defined in `.github/workflows/deploy.yml`
- It uses GitHub Actions to automatically build and deploy your site
- No build process needed - static HTML files are deployed directly

## Local Development

To view this site locally:
1. Clone the repository
2. Open `index.html` in your web browser
3. Navigate between pages using the navigation bar

## Pages Included:
- **Home** (`index.html`) - Landing page with hero image
- **About Me** (`about-me.html`) - Personal information
- **Portfolio** (`portfolio.html`) - Project showcase
- **Resume** (`resume.html`) - Professional resume

## Technologies Used:
- HTML5
- CSS3
- Bootstrap 4.5.2
- Google Fonts (Teko, Red Hat Text)
