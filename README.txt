XLIMITOZ WEBSITE — UPDATED BUILD
================================

WHAT WAS FIXED
- Kept the existing logo, button references, category names, admin dashboard, and resource features.
- Re-encoded the supplied homepage video to browser-friendly H.264 MP4 for improved mobile playback compatibility.
- Added a poster frame so the hero area shows a visual while the video is loading.
- Made the homepage and Explore Resources a separate screen. Tap Explore Resources to open the second page; tap Back to homepage or the logo to return.
- Added subtle floating glow effects, drifting particles, card entrance motion, and page transitions. Reduced-motion settings are respected.

FILES
- index.html
- assets/images/xlimitoz-logo.png
- assets/images/discord-reference.png
- assets/images/youtube-reference.png
- assets/images/video-poster.jpg
- assets/video/homepage.mp4

GITHUB PAGES
1. Extract the ZIP.
2. Upload index.html and the assets folder to the same root of your GitHub repository.
3. Enable GitHub Pages from Settings > Pages, selecting your main branch and root folder.
4. After publishing, open the live URL. If you previously deployed the old version, replace the old index.html and assets/video/homepage.mp4, then refresh the site (or clear browser cache).

ADMIN DEMO
Username: admin
Password: xlimitoz

IMPORTANT
This is a static frontend demo. Admin edits are stored only in the browser that made them and are not shared automatically with other visitors. The demo password is visible in the source and is not secure for a public website. For real shared editing/uploads, use server-side authentication and a backend/database with file storage.

The uploaded source video is 960x718, so converting it improves compatibility but does not create native 4K detail. The browser displays it using cover scaling to fill the hero area.
