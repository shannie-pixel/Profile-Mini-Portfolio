# Personal Profile & Mini-Portfolio
A personal profile and mini-portfolio website created using semantic HTML5.

# Accessibility

# Issue Found
uring the peer review, my peer noticed that some of the form labels were not correctly associated with their input fields.

# Fix Applied
I fixed this by making sure every form label has a `for` attribute that matches the `id` of its corresponding input. 
This allows users, including those using screen readers, to correctly identify each form field.


## Responsive Notes

### 1. Responsive Breakpoints Tested
The website is designed using a mobile-first approach and CSS media queries.

- **Mobile (375px):** Checked that the navigation wraps correctly, content fits the screen, and there is no horizontal scrolling.
- **Tablet (768px):** Checked that spacing increases and the skills section changes to four columns.
- **Desktop (1280px):** Checked that the content remains centred, sections have sufficient spacing, and the layout uses the available screen width.

### 2. Flexbox vs. CSS Grid
**Flexbox** is used for the navigation bar because it aligns links horizontally, maintains consistent spacing, and allows links to wrap on smaller screens. It is also used in the contact form to arrange fields vertically with consistent gaps.

**CSS Grid** is used for the skills and projects sections because it organises content into flexible columns. The skills grid displays two columns on mobile and four on tablet and desktop, while the projects grid adapts to wider screens.

### 3. Tailwind CSS Utilities
Tailwind utility classes are used in the following sections:

- **Header:** Controls text alignment, padding, font size and font weight.
- **Navigation:** Controls Flexbox layout, alignment, spacing and wrapping.
- **Contact form:** Controls the vertical Flexbox layout, spacing and responsive button width.

Responsive variants such as `sm:` and `md:` adjust styling at different screen sizes. Custom CSS in the `<style>` section handles the colour scheme, box model, Grid layouts, form appearance and media queries.

### 4. Commit History
The project was developed incrementally to document the styling process. The commits should reflect the actual changes made during development.

Examples of suitable commit messages include:

1. `Add base CSS styles and box model`
2. `Style header and navigation with Flexbox`
3. `Add CSS Grid for skills and projects`
4. `Add responsive media queries`
5. `Apply Tailwind utility classes`
6. `Refine spacing and improve accessibility`

