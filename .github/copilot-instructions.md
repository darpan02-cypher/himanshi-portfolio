# Himanshi Shrivas Portfolio - AI Coding Guidelines

## Project Overview
This is a static single-page portfolio website built with Bootstrap 5 and custom CSS. The site consists of a single `index.html` file with embedded styles and content sections.

## Architecture & Structure
- **Single File Design**: All content, styles, and structure in `index.html`
- **Section-based Layout**: Each major section (experience, skills, projects, etc.) uses `<section class="section" id="section-name">`
- **Bootstrap Grid**: Uses container/row/col-md-* classes for responsive layout
- **Navigation**: Fixed navbar with smooth scroll to section IDs

## Content Patterns

### Adding New Projects
Add to `.projects-grid` div in projects section:
```html
<div class="project-card">
  <div class="project-title">Project Name</div>
  <p>Description of the project and technologies used.</p>
  <div class="project-tech">
    <span class="tech-badge">Tech1</span>
    <span class="tech-badge">Tech2</span>
  </div>
</div>
```

### Adding Skills
Add to `.skills-grid` in skills section:
```html
<div class="skill-card" style="border: 2px solid #00f2fe; animation: glow 1.5s infinite alternate;">
  <span>Skill Name</span>
</div>
```
Alternate border colors: `#00f2fe` and `#4facfe`

### Adding Experience/Achievements
Use `.timeline-item` with `.timeline-content` for experience:
```html
<div class="timeline-item">
  <div class="timeline-content">
    <div class="timeline-title">Role Title</div>
    <div class="timeline-company">Company Name</div>
    <div class="timeline-date">Date Range | Location</div>
    <ul>
      <li>Key responsibility or achievement</li>
    </ul>
  </div>
</div>
```

## Styling Guidelines
- **Color Scheme**: Blue gradients (#00f2fe, #4facfe), dark backgrounds (rgba(0,0,0,0.8))
- **Typography**: Poppins font family, gradient text for headings
- **Animations**: fadeInUp, slideIn, hover transforms, glow effects
- **Cards**: Consistent padding (25-30px), border-radius (15-20px), hover effects
- **Responsive**: Mobile-first with media queries for tablets/desktop

## Development Workflow
- **No Build Process**: Direct edits to `index.html`
- **Testing**: Open in browser, check responsiveness on different screen sizes
- **Deployment**: Static hosting (GitHub Pages, Netlify, etc.)
- **Assets**: Background image referenced as `WhatsApp Image 2025-05-21 at 12.33.14.jpeg`

## Key Files
- `index.html`: Main portfolio file with all content and styles
- Background image in root directory

## Common Tasks
- Update hero stats in `.hero-stats`
- Add new achievements in `.row` under achievements section
- Modify contact info in `.contact-grid`
- Update navbar links to match section IDs</content>
<parameter name="filePath">/Users/himanshishrivas/himanshi-portfolio-1/.github/copilot-instructions.md