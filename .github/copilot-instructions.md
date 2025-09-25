# Copilot Instructions for Matthew's Portfolio

This project is a single-file static website (`index.html`) serving as a personal portfolio. There are no build tools, frameworks, or external dependencies—everything is hand-coded in HTML and CSS within one file.

## Project Structure
- **index.html**: Contains all markup, styles, and content. No JavaScript is present.
- No additional directories, assets, or configuration files are used.

## Key Patterns & Conventions
- **Inline CSS**: All styling is defined within a `<style>` block at the end of `index.html`. No external stylesheets.
- **Class Naming**: Classes use short, descriptive names (e.g., `.bod`, `.Welc`, `.About`, `.ab`, `.sidenav`).
- **Navigation**: The sidebar navigation is a fixed-position `<div class="sidenav">` with anchor links. All links are placeholders (`#`).
- **Content Organization**: Main sections are separated by headings and paragraphs. Personal information is presented in a conversational style.
- **No JavaScript**: There is currently no interactivity or scripting. If adding JS, keep it minimal and inline unless the project structure changes.

## Developer Workflow
- **Edit Directly**: Make all changes in `index.html`. No build or test steps are required.
- **Preview**: Open `index.html` in a browser to view changes. No local server is needed.
- **Accessibility**: Consider semantic HTML and color contrast if updating styles or content.

## Examples
- To add a new section, insert a new heading and paragraph within `<body>`, and style with a new class in the `<style>` block.
- To update navigation, modify the anchor tags inside `.sidenav`.

## Recommendations for AI Agents
- Keep all code in `index.html` unless the user requests a multi-file structure.
- Follow the existing class naming and inline CSS conventions.
- Ask for clarification before introducing frameworks, build tools, or external assets.
- Reference `index.html` for all examples and patterns.

---
If any conventions or workflows are unclear, ask the user for clarification before making major changes.
