# Progress Log

## Project Duration

The Portfolio Design project was actively developed over a period of 4 days, starting on June 10, 2024, and concluding on June 15, 2024.

## 2024-06-10 - Afternoon

### Project Setup

- Set up the project files, organizing them according to the planned architecture.
- Initialized the project on [GitHub](https://github.com/nicholasgillespie/portfolio-design), ensuring all initial files were committed and pushed.
- Began exploring Astro as the development tool for this project, diverging from the usual Vite setup. This involved:
  - Installing Astro via npm to ensure the latest version is used.
  - Going through the Astro documentation to understand the basics and how it differs from Vite.
  - Setting up a basic Astro project structure to get familiar with the file organization and component system.

## 2024-06-13 - Morning

### Design Review & Theme Setup

- Identified the sections, main elements/components, and the [macro layout](../design/01-composition.jpg).
- Defined the project [design tokens](https://github.com/nicholasgillespie/portfolio-design/tree/main/src/styles/00-settings).

## 2024-06-13 - Afternoon

### Section - solutions

- Implemented the "Solutions" section with responsive design and accessibility features:
  - Adjusting layouts for different screen sizes using CSS grid and flexbox.
  - Adding skip links for improved navigation and accessibility.

### Section - about

- Completed the "About" section, incorporating:
  - A responsive layout that adapts to all screen sizes.

## 2024-06-14 - Morning and Afternoon

Spent the morning and afternoon developing an accessible reel/carousel. The following progress has been made:

- Created the basic structure of the reel/carousel using HTML and CSS, ensuring it is fully responsive and accessible.
- Implemented JavaScript to dynamically adjust the scroll position of the reel, centering the content on load. This includes handling for both even and odd numbers of items in the reel.
- Applied custom styling to the scrollbar for enhanced visual appeal, while maintaining accessibility standards.

### To-Do:

- Convert the reel/carousel structure from `div` elements to a `ul` with `li` elements for better semantic HTML and accessibility.
- Refine scrollbar styling for better aesthetics and accessibility.
- Add accessible "Previous" and "Next" navigation buttons with keyboard support.
- Implement CSS Scroll Snap for smooth navigation, ensuring compatibility with keyboard controls.
- Use JavaScript to conditionally hide the scrollbar on page load, maintaining it if JavaScript is disabled.
- Test and adjust keyboard navigation to ensure a logical and intuitive flow through carousel items.

## 2024-06-15 - Morning

### Section - reel

- Converted the reel/carousel with a `ul` and `li` structure for improved semantics and accessibility.
- Removed the scrollbar for simplicity and visual appeal.
- Implemented JavaScript for dynamic centering of reel content and navigation button functionality.
- Added "Previous" and "Next" buttons with ARIA labels for accessible navigation.
- Integrated SkipLink for better navigation accessibility.

## 2024-06-15 - Afternoon

### Section - Slider

- Addressed and resolved spacing issues within the slider component to ensure consistent and visually appealing layout across different screen sizes.

### Section - Contact

- Developed the Contact section.

### General

- Site completion: With the finalization of the Contact section, all planned sections of the website are now developed and integrated. The site is fully functional and ready for final review and launch.

---

## [Date] - [Session]

### [Task Category]

- [Your tasks here]
