# Reflection on the Web Development Process

This reflection outlines the key learnings, challenges, and insights gained during the development of the Gillian Moore's B&B brochure website.

## What techniques were used to improve the accessibility of the website?

To improve the accessibility of the website, several techniques were employed, primarily focusing on adherence to WCAG 2.1 guidelines and the use of semantic HTML5:

*   **Semantic HTML:** Extensive use of HTML5 semantic elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`, `<article>`, `<aside>`) was crucial. This provides a clear and meaningful structure for assistive technologies, allowing screen readers to interpret content accurately and users to navigate efficiently. Headings (`<h1>` to `<h6>`) were used hierarchically to create a logical content outline.
*   **Text Alternatives for Images:** All relevant `<img>` tags were given descriptive `alt` attributes. This ensures that users who are visually impaired or whose browsers do not display images can still understand the content conveyed by the images.
*   **Keyboard Navigability:** All interactive elements, including navigation links, buttons, and form fields, were designed to be fully operable using only a keyboard. This was achieved by ensuring proper tab order and visible focus indicators, which are essential for users who cannot use a mouse.
*   **Color Contrast:** Attention was paid to maintaining sufficient color contrast between text and background elements to ensure readability for users with various visual impairments.
*   **Form Accessibility:** Form fields were explicitly associated with `<label>` elements using `for` and `id` attributes, making them accessible to screen readers. Placeholder text and `required` attributes were used to guide users.
*   **Responsive Design:** The website was developed with a mobile-first approach using CSS media queries, ensuring that the content is accessible and usable across a wide range of devices and screen sizes. This adaptability is a key aspect of universal design.
*   **Clear and Consistent Navigation:** A consistent navigation structure was maintained across all pages, enhancing predictability and ease of use for all users.

## What you would do differently if you had to undertake such a project again?

If I were to undertake a similar project again, I would consider the following improvements and changes:

*   **Automated Accessibility Testing:** While manual checks were performed, integrating automated accessibility testing tools (e.g., Lighthouse, Axe-core) into the development workflow from the outset would provide more comprehensive and consistent feedback on accessibility issues.
*   **User Testing with Diverse Users:** Conducting user testing with individuals with various disabilities would provide invaluable insights into real-world accessibility challenges and help identify areas for improvement that might be missed during development.
*   **CSS Preprocessor (Sass/Less):** For larger projects, using a CSS preprocessor would enhance maintainability, reusability, and organization of styles through features like variables, nesting, and mixins. While this project was small, it's a good practice for scalability.
*   **JavaScript Framework/Library (Vue/React/Angular):** For more dynamic content or complex interactions, adopting a lightweight JavaScript framework or library could streamline development and improve code organization, especially if the website were to grow beyond a simple brochure site. For this project, plain JavaScript was sufficient, but for future scalability, a framework would be considered.
*   **Version Control System (Git):** Although not explicitly used in this simulated environment, in a real-world scenario, a robust version control system like Git would be essential for tracking changes, collaborating with others, and managing different versions of the codebase.
*   **Content Management System (CMS):** For a B&B website, a simple CMS (e.g., WordPress, headless CMS) could empower the client to easily update content (room descriptions, prices, local attractions) without needing developer intervention. This would be a significant long-term benefit.
*   **Performance Optimization Tools:** Beyond basic image optimization, using tools for critical CSS, lazy loading images, and minifying assets would further enhance website performance and user experience.
*   **More Detailed UI/UX Mockups:** While a plan was made, more detailed wireframes and mockups before coding would help visualize the design more concretely and catch potential UI/UX issues earlier in the process.