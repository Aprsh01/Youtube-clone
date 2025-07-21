🧠 How It Works
This is a frontend-only YouTube homepage clone, built using HTML and CSS.
It is designed to look like the real YouTube homepage, but it's not functional (you can't play videos or search content). Here's how everything is put together:

📄 HTML Structure
The HTML file creates the overall layout of the page.

It is divided into 3 main parts:
  Header: Top bar that includes the YouTube logo, search bar, voice search, upload, notifications, and user profile.
  Sidebar: Left-side navigation with menu items like Home, Explore, Subscriptions, etc.
  Main Section: Grid layout that displays video thumbnails, titles, channel info, views, and duration.

🎨 CSS Styling
You used multiple CSS files:
  general.css for basic styles.
  header.css for the top navigation bar.
  sidebar.css for the left menu.
  video.css for styling the video grid layout.
Layouts are made using Flexbox and CSS Grid to align elements neatly.
Fonts are imported from Google Fonts (Roboto) to match YouTube’s look.

🖼️ Images
Icons like search, upload, and notifications are placed using .svg files.
Video thumbnails and channel profile pictures are stored in the thumbnails/ and yt-things/ folders.

💡 Notes
No JavaScript is used here — it's a static clone just for practicing layout and design.
This project helped practice:
Positioning (flex, grid)
Building reusable UI blocks (video cards)
Styling tooltips and icons
Working with fonts and images
