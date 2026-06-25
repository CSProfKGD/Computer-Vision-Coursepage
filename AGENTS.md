# Computer Vision Course Website

## Mission

Build a premium, modern course website for:

**A Visual and Technical Journey Into Computer Vision**

The site should modernize the legacy EECS 4422 course page while preserving its academic authority, lecture sequence, and resource links.

Use the existing **Deep Learning Coursepage** project as the primary local reference for:

- Visual style
- Layout structure
- Dark/light theme behavior
- Dynamic lecture rendering
- Resource organization
- Static-site simplicity

Avoid:

- Generic university templates
- Bootstrap-looking pages
- Dense walls of text
- Table-heavy layouts
- Outdated academic aesthetics
- Invented lecture links or placeholder URLs

## Source Of Truth

All course resources must come from:

- https://www.eecs.yorku.ca/~kosta/Courses/EECS4422/

This legacy page is authoritative.

Extract and preserve:

- Lecture PDF links
- MOV/video links
- Background material links
- Textbook references
- Useful links
- Acknowledgements
- Instructor and homepage links

Never invent URLs.

Never create guessed URLs.

If a resource does not exist, display:

`Coming Soon`

## Local Reference Project

Use the sibling project as the style and architecture reference:

- `/Users/kosta/Documents/Deep Learning Coursepage`

The new Computer Vision page should feel like a companion course in the same family, not a clone with swapped text.

Carry forward the proven structure:

- `index.html`
- `styles.css`
- `script.js`
- `data/course.json`
- Optional generated `data/course-data.js` for static hosting compatibility
- `README.md`

## Theme

Default theme: dark mode.

Requirements:

- Dark mode by default
- Light mode toggle
- `localStorage` persistence
- Accessible contrast in both themes
- York University logo variants for dark and light themes when available

## Visual Style

The website should feel:

- Premium
- Elegant
- Modern
- Academic
- Visual
- Approachable

Use:

- Large typography
- Generous whitespace
- Subtle motion
- Refined color palette
- Rounded cards with radius no larger than 8px unless matching the reference project
- Soft shadows
- Clear lecture grouping

Lecture cards should remain the primary visual focus.

Use the Deep Learning Coursepage design language, but tune the Computer Vision palette and imagery around visual perception, geometry, motion, image formation, and recognition.

## Layout

Desktop:

- Centered content
- Constrained width
- Multi-column lecture card grid
- Strong hero section with course identity and instructor presence

Tablet:

- Responsive reflow
- Comfortable navigation and category controls

Mobile:

- Single-column lecture card layout
- Comfortable spacing
- Large tap targets
- No horizontal scrolling

## Accessibility

Use:

- Semantic HTML
- Proper heading hierarchy
- Alt text
- Keyboard navigation
- Visible focus states
- ARIA labels where appropriate

## Lecture Data

All lecture content should be rendered dynamically from:

- `data/course.json`

Do not hardcode lecture cards into HTML.

Each lecture entry should preserve the original lecture title and links from the legacy page.

Each lecture may also include a modern display title and one-sentence description for the new experience.

## Link Accuracy

Before finalizing, verify every lecture PDF, MOV/video link, background-material link, textbook link, useful link, and instructor link against the York course page.

Never substitute missing resources.

Never rewrite external links unless the source page itself contains the newer URL.

## Lecture Descriptions

For every lecture description:

- Use exactly one sentence
- Use 15-25 words
- Focus on intuition
- Focus on motivation
- Avoid marketing language
- Maintain a consistent tone

## Content Priorities

The new site should make the learning path obvious:

1. Course identity and overview
2. Instructor information
3. Lecture journey
4. Background readings and supporting materials
5. Reference textbooks
6. Useful links
7. Acknowledgements

## Validation

After implementation, generate screenshots at:

- 1440px
- 1024px
- 768px
- 430px
- 390px

Review:

- Typography
- Spacing
- Hierarchy
- Responsiveness
- Theme switching
- Lecture-card clarity
- Link rendering

Fix issues before finalizing.

## Self Review

Before final delivery, confirm that the answer is yes to all six questions:

1. Does this feel modern?
2. Does this feel premium?
3. Is the computer vision learning journey obvious?
4. Are lecture cards the visual focus?
5. Is mobile excellent?
6. Would a student immediately want to explore?

Iterate until the answer is yes to all six.

## TODO Comments

Add TODO comments for:

- Replacing instructor portrait if needed
- Updating social links if newer official profiles are provided
- Future lecture additions
- Future course customization
- Any resource that is intentionally shown as `Coming Soon`
