# Product Preview Card Component

## Overview

This is my solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-). The challenge required building a responsive product card that displays a perfume product with its image, description, pricing, and an "Add to Cart" button. The design needed to adapt seamlessly from mobile to desktop views while maintaining visual consistency and accessibility.

## The Challenge

Users should be able to view the optimal layout depending on their device's screen size, see hover and focus states for interactive elements, and experience a clean, modern design that follows the provided style guide. The component needed to be built with a mobile-first approach, using semantic HTML5 markup and CSS with responsive design techniques.

## My Approach

I built this project using a mobile-first workflow, starting with the smallest screen size and progressively enhancing the layout for larger screens. The card uses CSS Flexbox for layout structure, with a vertical column arrangement on mobile that switches to a horizontal two-column layout on desktop. I implemented responsive typography using the `clamp()` function for fluid text sizing that scales smoothly across all devices.

For the visual design, I incorporated the specified color palette including the primary green tones (hsl(158, 36%, 37%) and hsl(158, 42%, 18%)) and neutral shades. The typography combines Montserrat for body text and Fraunces for the product title, creating an elegant contrast that matches the luxury perfume branding. The card includes interactive states with hover effects on the "Add to Cart" button, changing from the primary green to a darker shade for better user feedback.

One of the key challenges was handling the product images responsively. I used CSS background images with media queries to switch between mobile and desktop versions, ensuring the appropriate image loads at each breakpoint. The card structure includes proper ARIA labels and semantic HTML elements for accessibility, making the component usable for all visitors.

The responsive behavior is managed through three main breakpoints: mobile (default up to 768px), tablet/desktop (768px and above), and large screens (1024px and above). The card's maximum width expands slightly on larger screens while maintaining readability and visual hierarchy. The spacing, padding, and font sizes are carefully adjusted at each breakpoint to create a polished experience.

## Built With

- Semantic HTML5 markup
- CSS custom properties for consistent theming
- Flexbox for flexible layout management
- Mobile-first responsive design approach
- Fluid typography using CSS `clamp()` function
- Media queries for breakpoint-specific adjustments
- Google Fonts (Montserrat and Fraunces)
- CSS transitions for smooth interactive states

## Key Features

- Fully responsive design that adapts from 320px to large screens
- Mobile-first approach with progressive enhancement
- Fluid typography that scales with viewport size
- Hover and focus states for better interactivity
- Accessible with proper ARIA labels and semantic HTML
- Clean separation of concerns between HTML structure and CSS styling
- Optimized image loading with mobile and desktop versions

## What I Learned

This project reinforced the importance of starting with a mobile-first approach and using relative units like `em` and `rem` for scalable, accessible designs. I gained practical experience with the `clamp()` function for fluid typography, which provides better control over text sizing compared to viewport units alone. The challenge also helped me understand how to structure responsive layouts using Flexbox effectively, particularly when transitioning between column and row arrangements at different breakpoints.

Working with background images and media queries taught me how to handle responsive images efficiently without relying on JavaScript. I also improved my understanding of CSS specificity, cascade, and how to organize styles in a maintainable way. The project highlighted the importance of testing across multiple screen sizes and devices to ensure a consistent user experience.

## Future Improvements

While the current implementation meets all challenge requirements, there are areas I could enhance further. I could implement a more sophisticated image loading strategy using the `<picture>` element with `srcset` for better performance. Adding smooth animations for the card appearance and button interactions would elevate the user experience. I could also explore using CSS Grid alongside Flexbox for more complex layouts, and implement a dark mode option that respects user preferences.

For production use, I would add form validation for the cart interaction, implement state management for the add-to-cart functionality, and add comprehensive testing across different browsers and devices. The component could also be extended to support multiple product variations and include quantity selectors for a more complete e-commerce experience.

## Acknowledgments

- [Frontend Mentor](https://www.frontendmentor.io) for providing the challenge and design files
- [Google Fonts](https://fonts.google.com) for the typography resources
- Kevin Powell's "Conquering Responsive Layouts" course for fundamental responsive design concepts

## Results

## Desktop View

![Descktop Screenshot](./design/desktop-design.jpg)

## Mobile View

![Mobile Scrrenshot](./design/mobile-design.jpg)

## Active View

![Active Screenshot](./design/active-states.jpg)

## Links

- [[Solution URL](https://github.com/Kelvyn94/product-preview-card)]
- [[[Live Site URL](https://kelvyn94.github.io/product-preview-card/)]]

## Author

- Frontend Mentor - [[@your-username](https://www.frontendmentor.io/profile/Kelvyn94)]
- GitHub - [[@your-username](https://github.com/Kelvyn94)]
