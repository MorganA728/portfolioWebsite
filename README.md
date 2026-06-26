# Personal Portfolio Website

This is a static personal portfolio website built with HTML, CSS, and JavaScript. You can edit it in VS Code and host it with the Live Server extension, GitHub Pages, Netlify, Vercel, or any static hosting service.

## Files

- `index.html` — main page content
- `styles.css` — all layout, colors, and responsive styling
- `script.js` — mobile menu and automatic footer year
- `resume.pdf` — optional file you can add yourself if you want the resume button to work

## How to edit

Open the folder in VS Code and replace:

- `Your Name`
- `YN` in the logo
- `your.email@example.com`
- LinkedIn and GitHub URLs
- Project descriptions and project links
- Experience entries
- Resume file

## How to preview with VS Code

1. Install the VS Code extension called **Live Server**.
2. Open this folder in VS Code.
3. Right-click `index.html`.
4. Click **Open with Live Server**.

## How to host with GitHub Pages

1. Create a new GitHub repository.
2. Upload these files to the repository.
3. Go to repository **Settings**.
4. Open **Pages**.
5. Set the source to your main branch.
6. Save and wait for GitHub to publish the site.

## Quick customization

To change the main accent color, open `styles.css` and edit this line:

```css
--accent: #38bdf8;
--accent-dark: #0284c7;
```

To add your own profile picture:

1. Add an image file to the folder, for example `profile.jpg`.
2. In `index.html`, replace this block:

```html
<div class="profile-placeholder">
  <span>Photo</span>
</div>
```

with:

```html
<img class="profile-image" src="profile.jpg" alt="Your Name profile photo" />
```

3. Add this to `styles.css`:

```css
.profile-image {
  width: 180px;
  height: 180px;
  margin: 0 auto 24px;
  border-radius: 50%;
  object-fit: cover;
  display: block;
}
```
