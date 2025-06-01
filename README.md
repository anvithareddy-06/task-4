# Responsive Web Page using CSS Media Queries
This project converts a static, desktop-only webpage into a **mobile-friendly** layout using **CSS media queries**. The page layout adjusts for smaller screen sizes (like phones and tablets), improving usability and readability.

## Objective
- Make an existing HTML page responsive on mobile devices.
- Use `@media` queries to adjust layout, font sizes, and navigation.
- Eliminate horizontal scrolling and layout breaking on small viewports.

## Tools Used
- HTML5
- CSS3 with Media Queries
- [VS Code](https://code.visualstudio.com/)
- [Google Chrome DevTools](https://developer.chrome.com/docs/devtools/)

## Features
- Responsive design for screens smaller than 768px.
- Navigation menu stacks vertically on mobile.
- Sidebar and content stack for better mobile readability.
- Scalable images using `max-width: 100%`.
- Fixed overflow and font scaling for better mobile UX.

## Media Query Used
@media (max-width: 768px) {
  /* Adjust layout for mobile screens */
  .navbar {
    flex-direction: column;
    align-items: center;
  }

  .content {
    flex-direction: column;
  }

  .sidebar,
  .main {
    width: 100%;
  }

  body {
    font-size: 14px;
  }

  img {
    max-width: 100%;
    height: auto;
  }
}

**How to Run**
1. Clone the repo or download the files.
2. Open basic.html in your browser.
3. Use Chrome DevTools to toggle device toolbar (Ctrl + Shift + M).
4. Test the layout on various screen sizes.
