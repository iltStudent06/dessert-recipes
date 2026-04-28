## Why you structured the HTML the way you did 

I structured the HTML files using a clear and consistent layout so the website is easy to read, style, and maintain. Each page follows a similar structure with a head, body, header, main content area, and footer.

All visible page content is placed inside the <body>. This includes the header, images, text, forms, recipe cards, and footer. Keeping everything inside the <body> is important because it ensures the page displays correctly in the browser.

Each page uses the same header structure: website title, tagline, and navigation menu. This is done for consistency across all pages so users can move easily between the homepage, about page, and contact page. It also makes the site feel unified.

Each page has main content inside a <main> element. This helps separate the primary page content from repeated content like the header and footer.

Inside <main>, content is divided into sections depending on the page. This makes the code easy to read and allows each area of the page to be styled separately.

Semantic tags like <header>, <nav>, <main>, <section>, <article>, and <footer> are used throughout the project. These tags are used instead of only <div> elements because they describe the purpose of the content more clearly. This consistency makes the project easy to build and update. If changes are needed later, such as adding new navigation links or updating the footer, the same updates can be made across every page.

I structured the HTML files this way to:

1. keep the code clean and organized
2. use semantic HTML for clarity and accessibility
3. make the website easy to style with CSS
4. create consistency across all pages
5. support responsive design and footer layout
6. improve maintainability as the project grows

## Your CSS layout approach and organizational strategy 

I designed the CSS files to create a clean, responsive, and consistent layout across multiple pages.

Common elements such as the header, navigation, section titles, buttons, and footer are styled in a similar way across the homepage, about page, and contact page. This creates a unified look by reusing:

1. the same color palette
2. similar fonts
3. consistent spacing
4. matching navigation and footer styles

To control alignment and spacing, Flexbox is used in the navigation bar, the about page content layout, and footer links.

On the homepage, CSS Grid is used to organize recipe cards into a responsive card layout. This allows the cards to automatically adjust based on screen size.

The CSS files include media queries to improve website usability on smaller screens. These responsive rules adjust font sizes, image heights, navigation spacing, and layout direction when the screen becomes narrower. For example, the recipe cards change from multiple columns to one column and the about page shifts from side-by-side content to stacked content. This ensures the website remains usable and visually balanced on different device sizes.

The CSS files use descriptive class names that match the purpose of each part of the page. This makes the code easier to read and easier to connect to the HTML structure.

Images are styled to scale properly within their containers and work across different screen sizes.

Each page has its own CSS file. This keeps page-specific styling separate and easier to manage. At the same time, the files follow a similar pattern and reuse the same design so the project stays consistent.

This strategy is helpful for a beginner project because it keeps each page manageable.

## Accessibility considerations and how you addressed them 

I wanted to make the website usable, easy to understand, and accessible to a broad audience so I

1. used semantic HTML instead of only generic <div> elements
2. added alt text to images
3. paired labels with form inputs
4. kept navigation consistent across pages
5. used responsive design for different screen sizes
6. organized content into clearly separated sections

## Your responsive design strategy (mobile-first vs. desktop-first and why) 

I used a desktop-first responsive design strategy since this is a recipe website. In my CSS files, the default styles are written for larger screens first and then I used media queries with max-width to adjust the layout for smaller devices. The media queries help to stack content, resize images, and simplify layouts on mobile screens.
