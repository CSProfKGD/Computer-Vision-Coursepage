# EECS 4422 Computer Vision Course Website

Modern static course page for **A Visual and Technical Journey Into Computer Vision**.

The legacy source of truth is:

- https://www.eecs.yorku.ca/~kosta/Courses/EECS4422/

The site follows the style and static architecture of the sibling Deep Learning Coursepage project.

## Files

- `index.html` - page shell and semantic sections
- `styles.css` - dark-first responsive theme
- `script.js` - dynamic rendering and theme toggle
- `data/course.json` - authoritative structured course content
- `data/course-data.js` - static fallback for opening the page directly
- `assets/` - York branding and instructor portrait

## Local Preview

From this folder:

```sh
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```
