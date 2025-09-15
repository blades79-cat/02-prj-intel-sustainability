
# Copilot Instructions: Intel Sustainability Journey Webpage

## Audience & Coding Style
- Students are beginners learning HTML and CSS.
- Always provide the simplest, beginner-friendly code possible.
- Use clear comments to explain each part of the code.
- Do **not** use advanced CSS layout methods (like grid or flexbox) unless specifically requested.

## Project Structure
- Main files:
	- `index.html`: The single-page app containing all content and structure.
	- `style.css`: All custom styles for the page.
	- `img/`: Contains images for timeline cards and the Intel logo (SVG and JPGs).
- No JavaScript or build tools are used; this is a static HTML/CSS project.

## Key Patterns & Conventions
- Timeline events are represented as a series of `<div>` cards inside a single `<section>` in `index.html`.
- Each card includes a year, title, and description. Images are referenced from the `img/` folder but may need to be added to each card.
- The header uses the SVG logo (`img/intel-header-logo.svg`) and a main heading.
- Responsive design is encouraged, but only with basic CSS (media queries, relative units).
- Use semantic HTML where possible (e.g., `<header>`, `<section>`, `<h1>`, `<h2>`, `<p>`).
- All code should be well-commented for educational clarity.

## Developer Workflow
- Edit `index.html` and `style.css` directly; changes are reflected immediately in the browser.
- No build, test, or deployment steps are required—just open `index.html` in a browser.
- When adding images, use relative paths (e.g., `img/1.jpg`).
- Commit and push changes regularly if using Codespaces or GitHub.

## Example: Adding an Image to a Timeline Card
```html
<div>
	<h2>1971</h2>
	<h3>First Microprocessor</h3>
	<img src="img/2.jpg" alt="Intel 4004 Microprocessor" />
	<p>Intel debuts the 4004, ...</p>
</div>
```

## Additional Notes
- Do not introduce frameworks, preprocessors, or external dependencies.
- Keep all code and comments accessible for beginners.

Refer to `README.md` for the project goal and learning objectives.
