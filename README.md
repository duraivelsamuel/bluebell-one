# Bluebell One

A fee management app for nursing colleges, built as a single HTML file with a Cloudflare Workers backend.

## Features
- Track student fees across multiple nursing colleges
- Payment recording with lock/unlock workflow
- Role-based access (admin / editor)
- Summary reports by batch and course
- Works offline with local storage fallback

## Setup
1. Replace the placeholder credentials in `index.html` with your own
2. Deploy the Cloudflare Worker backend (see backend setup)
3. Upload all files to your web host or use GitHub Pages

## Images
Add your own photos (same folder as index.html):
- `slide1.jpg` – `slide5.jpg` : Dashboard slider (1200×480px)
- `col-jubilee.jpg`, `col-sneha.jpg`, `col-vijayanagar.jpg`, `col-prestige.jpg`, `col-antony.jpg` : College thumbnails (400×300px)

Built with vanilla JS, no frameworks.
