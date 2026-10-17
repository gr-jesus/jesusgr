# Academic Portfolio - Dr. Jesús García-Ramírez

This repository contains the source code for my personal and academic website. The design is focused on minimalism and efficiency, inspired by researcher profiles from top-tier institutions, allowing the trajectory, publications, and achievements to take center stage.

The site is built as an extremely lightweight Single Page Application (SPA) using only HTML5, native CSS, and Vanilla JavaScript within a single file.

## 🌐 Site Structure

The portfolio is divided into the following navigable sections (without page reloads):

* **Home / Bio:** Professional summary, research interests, notable awards, and contact links.

* **Publications:** Complete and updated list of scientific articles, conferences, and reports.

* **Teaching:** Teaching experience at the undergraduate and graduate levels.

* **CV:** Direct link to download the Curriculum Vitae in PDF format.

## 🛠️ Update and Maintenance Instructions

Being designed in a single file (`index.html`), maintenance is very simple:

### 1. Updating the Profile Picture

1. Upload your photo to the repository (e.g., `profile.jpg`).

2. Open the `index.html` file.

3. Find the `<img src="https://placehold.co/150x200..." ...>` tag and change the URL to your file's name:

   ```html
   <img src="profile.jpg" alt="Jesus Garcia-Ramirez" class="profile-pic">
   ```

### 2. Updating the CV

To update your resume, simply replace the `CV_Español.pdf` file in the root of this repository with your most recent version. Make sure to keep exactly the same file name so the top menu link continues to work (or update the filename in the `index.html` file to match).

### 3. Adding New Publications

Go to the `<div id="publications" class="section">` section in the `index.html` file and add a new list item (`<li> ... </li>`) inside the `<ol>` tag.

## 🚀 Deployment

This site is designed to be hosted for free and automatically through **GitHub Pages**:

1. Go to the **Settings** tab of this repository.

2. On the left sidebar menu, select **Pages**.

3. Under **Source**, select `Deploy from a branch`.

4. Under **Branch**, select `main` (or `master`) and the `/ (root)` folder.

5. Save the changes. In a couple of minutes, your site will be live.

*Developed for scientific and academic dissemination.*