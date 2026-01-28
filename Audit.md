## HTML Issues

1. Missing or incorrect semantic tags  
   - What is wrong: The HTML uses too many generic `<div>` elements instead of semantic tags like `<header>`, `<nav>`, `<main>`, and `<footer>`.  
   - Why it is a problem: This reduces accessibility, makes the structure harder to understand, and negatively affects SEO.  
   - What we plan to change: Replace generic containers with proper semantic HTML elements.

2. Images missing alt attributes  
   - What is wrong: Some `<img>` tags do not include `alt` text.  
   - Why it is a problem: Screen readers cannot describe images to visually impaired users, reducing accessibility compliance.  
   - What we plan to change: Add meaningful `alt` attributes to all images.

3. Improper heading hierarchy  
   - What is wrong: Heading levels skip order (e.g., `<h1>` directly followed by `<h3>`).  
   - Why it is a problem: This breaks document structure and confuses screen readers and search engines.  
   - What we plan to change: Reorder headings so they follow a logical hierarchy.

4. Missing meta viewport tag  
   - What is wrong: The `<meta name="viewport">` tag is missing or incorrectly configured.  
   - Why it is a problem: The site will not scale properly on mobile devices.  
   - What we plan to change: Add a correct viewport meta tag for responsive design.

5. Unclosed or improperly nested tags  
   - What is wrong: Some HTML tags are not properly closed or are nested incorrectly.  
   - Why it is a problem: This can cause layout issues and unpredictable browser behavior.  
   - What we plan to change: Validate and correct all HTML tag structures.

---

## CSS Issues

1. Use of fixed units instead of responsive units  
   - What is wrong: CSS uses fixed values like `px` for widths and heights.  
   - Why it is a problem: This prevents the layout from adapting to different screen sizes.  
   - What we plan to change: Replace fixed units with relative units such as `%`, `em`, or `rem`.

2. Repeated or redundant CSS rules  
   - What is wrong: Several CSS rules repeat the same styles for different selectors.  
   - Why it is a problem: This increases file size and makes maintenance harder.  
   - What we plan to change: Refactor repeated styles into shared classes.

3. Poor class naming conventions  
   - What is wrong: Class names are unclear or inconsistent (e.g., `box1`, `style2`).  
   - Why it is a problem: This makes the CSS difficult to read and maintain.  
   - What we plan to change: Rename classes using clear, descriptive naming conventions.

4. Missing hover or focus states  
   - What is wrong: Buttons and links lack hover or focus styles.  
   - Why it is a problem: Users receive no visual feedback during interaction, harming usability.  
   - What we plan to change: Add hover and focus styles for interactive elements.

5. Inline styles used in HTML  
   - What is wrong: Some styling is applied directly in HTML using `style` attributes.  
   - Why it is a problem: Inline styles break separation of concerns and are harder to maintain.  
   - What we plan to change: Move all inline styles into the external CSS file.

---

## Git / Structure Issues

1. No clear folder structure  
   - What is wrong: HTML, CSS, and assets are mixed in the root directory.  
   - Why it is a problem: This makes the project harder to navigate and scale.  
   - What we plan to change: Organize files into folders such as `/css`, `/images`, and `/js`.

2. Missing README documentation  
   - What is wrong: The project lacks a `README.md` file explaining the project.  
   - Why it is a problem: New contributors do not understand the purpose or setup of the project.  
   - What we plan to change: Add a clear README with project details and setup instructions.

3. No `.gitignore` file  
   - What is wrong: The repository does not include a `.gitignore`.  
   - Why it is a problem: Unnecessary or system files may be committed.  
   - What we plan to change: Add a `.gitignore` to exclude irrelevant files.

4. Large commits with multiple changes  
   - What is wrong: Changes are grouped into large commits instead of smaller logical ones.  
   - Why it is a problem: This makes tracking changes and debugging more difficult.  
   - What we plan to change: Use smaller, well-described commits moving forward.

5. Inconsistent file naming  
   - What is wrong: File names use inconsistent casing and formats.  
   - Why it is a problem: This can cause confusion and issues on case-sensitive systems.  
   - What we plan to change: Standardize file naming conventions across the project.
