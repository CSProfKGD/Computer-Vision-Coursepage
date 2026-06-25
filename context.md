# Course Website Content

## Title

A Visual and Technical Journey Into Computer Vision

## Course

EECS 4422 Computer Vision

## Subtitle

From image formation and filtering to motion, 3D structure, and recognition.

## Instructor

Kosta Derpanis

Prof. Kosta Derpanis, York University

Hero section should include:

- York University branding
- Instructor portrait if available locally
- Instructor name
- Title
- Homepage link
- Contact link or obfuscated email text

Use links from:

- https://www.eecs.yorku.ca/~kosta/Courses/EECS4422/

Add a TODO comment where the instructor portrait should be replaced or updated.

## Course Overview

This course introduces the fundamental concepts of computer vision with emphasis on computer science and engineering.

The course covers image formation, image representation, feature extraction, stereopsis, motion analysis, 3D parameter estimation, and applications.

The new website should present these topics as a coherent journey from pixels and cameras to visual understanding.

## Primary Textbook

Richard Szeliski, **Computer Vision: Algorithms and Applications**

The legacy page links to the free online version and notes that the book can also be purchased.

## Journey Section

Title:

The Journey

Display lectures as premium cards.

Each card should contain:

- Modern display title
- Original lecture title
- Course topic grouping
- One-sentence description
- PDF/slides link
- MOV/video link
- Background material links when available
- Reading references

Missing resources should display:

`Coming Soon`

## Topic List

### Background Material

0. Introduction to computer vision
   - Reading: Szeliski, Chapter 1
   - Background: Eero Simoncelli, A Geometric Review of Linear Algebra

### Image Formation

1. Image formation (part 1)
   - Reading: Szeliski, Chapter 2, Section 2.1
   - Background: History of Photography in 5 Minutes

2. Image formation (part 2)

3. Image transformations

4. Image metrology
   - Background: Bringing Pictorial Space to Life

### Image Filtering And Feature Extraction

5. Image filtering: Smoothing
   - Reading: Szeliski, Chapter 3, Sections 3.1 to 3.2.2

6. Image filtering: Edge detection
   - Reading: Szeliski, Chapter 4, Section 4.2
   - Background: Pedro Felzenszwalb, Edge Detection
   - Background: Avidan and Shamir, Seam Carving for Content-Aware Image Resizing

7. Image features
   - Reading: Szeliski, Chapter 4, Section 4.1

### Model Fitting

8. Model fitting
   - Reading: Szeliski, Chapter 4, Section 4.3.2, and Chapter 6, Sections 6.1.1, 6.1.2, and 6.1.4
   - Background: Ballard and Brown, Hough transform

### Frequency Analysis

9. Frequency analysis: Theory
   - Reading: Szeliski, Chapter 3, Section 3.4

10. Frequency analysis: Applications
    - Reading: Horn, Chapters 6 and 7

11. Image Pyramids

### Multiple Image Analysis

12. Motion analysis
    - Reading: Trucco and Verri, Chapter 8, Sections 8.3 and 8.4
    - Background: Fleet and Weiss, Optical Flow Estimation, Sections 1 and 2

13. Stereopsis
    - Reading: Trucco and Verri, Chapter 7

14. Camera Calibration

15. 3D structure and motion
    - Reading: Trucco and Verri, Chapter 8, Sections 8.1 and 8.2

16. Tomasi and Kanade Factorization Method
    - Background: Tomasi and Kanade, Shape and Motion from Image Streams under Orthography: A Factorization Method

17. Procrustes analysis

### Recognition

18. Machine learning crash course

## Reference Textbooks

- Gilbert Strang, **Linear Algebra and Its Applications**
- Berthold Horn, **Robot Vision**, MIT Press
- Emanuele Trucco and Alessandro Verri, **Introductory Techniques for 3-D Computer Vision**, Prentice Hall

Include authoritative links from the legacy course page where available.

## Useful Links

The legacy course page includes:

- Python Numpy tutorial
- Basic Linear algebra review
- Linear algebra review and reference

Preserve these links in the new resource section.

## Acknowledgements

The legacy page acknowledges that many lecture slides rely significantly on material prepared by the following instructors:

- Richard Wildes
- Kostas Daniilidis
- James Hays
- Derek Hoiem
- Aaron Bobick
- David Lowe
- Kristen Grauman
- Robert Collins
- Svetlana Lazebnik
- Steve Seitz
- William Freeman
- Robert Pless
- Andrej Karpathy
- Alyosha Efros

The new website should preserve this acknowledgement in a concise, respectful section.

## Suggested Lecture Display Titles

Use these as editable starting points when building `data/course.json`:

1. Teaching Machines to See
2. How Images Are Made
3. Cameras, Light, and Projection
4. Warping the Visual World
5. Measuring From Images
6. Smoothing the Signal
7. Finding Edges
8. Detecting Visual Structure
9. Fitting Models to Evidence
10. Seeing in Frequencies
11. Filtering in the Frequency Domain
12. Images Across Scale
13. Understanding Motion
14. Seeing in Stereo
15. Calibrating Cameras
16. Reconstructing 3D Worlds
17. Factoring Shape and Motion
18. Aligning Shapes
19. Recognizing Patterns

## Implementation Notes

Use the Deep Learning Coursepage as the companion design system:

- Dark-first theme with a light-mode toggle
- Sticky York-branded header
- Large editorial hero
- Instructor panel
- Category navigation
- Dynamic lecture cards
- Resource sections
- Static hosting compatibility

The Computer Vision page should distinguish itself through content, imagery, copy, and topic groupings rather than structural novelty.
