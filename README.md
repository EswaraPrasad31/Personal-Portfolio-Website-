# Personal Portfolio (N Eswara Prasad)

A responsive personal portfolio website built with **HTML**, **CSS**, **Bootstrap 5**, and a small amount of **JavaScript**.

## Features

- Sticky/animated Bootstrap navbar with active section highlighting
- Smooth scrolling + section reveal animation (IntersectionObserver)
- Sections:
  - Home
  - About
  - Skills
  - Projects
  - Achievements
  - Contact
- Dark themed UI with custom gradients and card styling

## Project Structure

```text
.
├─ index.html
├─ styles.css
├─ images/
│  └─ profile.jpg
├─ screenshots/
│  ├─ home.png
│  ├─ about.png
│  ├─ skills.png
│  ├─ projects.png
│  ├─ achievements.png
│  └─ contact.png
└─ RESUME.pdf
```

## How to Run

This is a static site.

1. Open `index.html` in your browser.
2. (Optional) If you want the best experience with local hosting, you can run a static server, e.g. from your editor or any “Live Server” extension.

## Technologies Used

- **Bootstrap 5.3.3** (CDN)
- **Google Fonts** (Poppins)
- CSS animations and custom styling
- JavaScript:
  - Scroll listener for navbar active state
  - IntersectionObserver for reveal animations

## Notes / Customization

- Update the profile image by replacing `images/profile.jpg`.
- Update contact details and text directly in `index.html`.
- To change section names/links, update both the navbar links and the corresponding `<section id="...">` elements.
- The resume download button links to `RESUME.pdf` (ensure the file exists).

## License

Add your preferred license information here (e.g., MIT, Apache-2.0).
