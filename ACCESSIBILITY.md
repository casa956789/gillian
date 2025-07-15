# Accessibility Statement for Gillian Moore's B&B Website

This document outlines the accessibility features and techniques implemented in the Gillian Moore's B&B website, aiming to make it usable by the widest possible audience, regardless of ability or technology. Our goal is to adhere to Web Content Accessibility Guidelines (WCAG) 2.1 principles.

## Key Accessibility Features Implemented:

### 1. Perceivable

*   **Text Alternatives for Non-Text Content:**
    *   All meaningful images (`<img>` tags) across the website include descriptive `alt` attributes. This provides equivalent information for users who cannot see the images (e.g., screen reader users). Decorative images have empty `alt` attributes (`alt=""`).
    *   Example: `<img src="images/bnb-exterior-1.jpg" alt="Front view of Gillian Moore's Bed and Breakfast with a garden.">`
*   **Semantic HTML Structure:**
    *   The website utilizes HTML5 semantic elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`, `<article>`, `<aside>`) to clearly define the structure and meaning of content. This allows assistive technologies to interpret and navigate the content more effectively.
    *   Headings (`<h1>` to `<h6>`) are used hierarchically to organize content, providing a clear outline for screen readers and improving readability.
*   **Color Contrast:**
    *   Care has been taken to ensure sufficient color contrast between text and background elements to meet WCAG 2.1 AA standards, making content readable for users with low vision or color blindness.
*   **Distinguishable Content:**
    *   Information is not conveyed by color alone. For example, interactive elements are distinguished by both color and underline/bolding on hover.

### 2. Operable

*   **Keyboard Navigation:**
    *   All interactive elements, including navigation links, buttons, and form fields, are fully accessible and operable using only a keyboard. A logical tab order is maintained throughout the site.
    *   Focus indicators (e.g., outlines on focus) are provided for interactive elements to clearly show keyboard users where they are on the page.
*   **Clear and Consistent Navigation:**
    *   The main navigation menu is consistent across all pages, providing a predictable and easy-to-understand way to move through the website.
    *   Skip links (though not explicitly visible, can be implemented via CSS for screen readers) are considered to allow users to bypass repetitive navigation blocks.
*   **Form Accessibility:**
    *   All form fields (`<input>`, `<textarea>`) are associated with explicit `<label>` elements using the `for` and `id` attributes, improving usability for screen reader users.
    *   Placeholder text provides hints, and `required` attributes are used for mandatory fields.

### 3. Understandable

*   **Readable Content:**
    *   Clear and concise language is used throughout the website.
    *   Font choices and sizes are selected for optimal readability.
*   **Predictable Behavior:**
    *   The layout and functionality of the website are consistent across pages, ensuring a predictable user experience.
*   **Input Assistance (Forms):**
    *   Form fields have clear labels and instructions. Client-side validation (via HTML5 `required` attribute and potentially JavaScript) provides immediate feedback to users.

### 4. Robust

*   **Valid HTML5 and CSS:**
    *   The website is built using valid HTML5 and CSS, ensuring compatibility with a wide range of user agents, including current and future assistive technologies.

## Ongoing Commitment:

We are committed to continually improving the accessibility of our website. If you encounter any accessibility barriers or have suggestions for improvement, please do not hesitate to contact us.