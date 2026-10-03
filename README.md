# Chinese Home Kitchen

**CSC 6370 – Project 1**  
**Track:** Recipe Studio  
**Extension Pack:** Story Pack  

## Team Members

- Yalin Zhang
- Yunxue Wu

## Project Overview

Chinese Home Kitchen is a responsive recipe website inspired by Chinese home-cooked food. The project introduces six familiar dishes and combines simple recipe content with warm food stories and a clean, modern visual style.

The website includes four main pages:

- **Home** – Introduces the website and highlights featured recipes.
- **Recipes** – Displays six Chinese dishes in a responsive recipe card grid.
- **Recipe Detail** – Presents a detailed Mapo Tofu recipe using the Story Pack format.
- **About** – Introduces the project, team members, and a contact form.

The design uses a warm cream, dusty rose, soft white, dark brown, and muted gold color palette to create a simple and welcoming home-kitchen atmosphere.

## Featured Recipes

The website features six Chinese home-style dishes:

- Dumplings
- Tomato and Egg
- Mapo Tofu
- Kung Pao Chicken
- Fried Rice
- Braised Pork
## Story Pack

The Recipe Detail page uses the Story Pack extension to present the recipe as a five-part cooking journey:

1. **The Story** – Introduces the background of the dish.
2. **Ingredients** – Lists the ingredients needed for the recipe.
3. **Preparation** – Explains how to prepare the ingredients.
4. **Cooking** – Provides the main cooking steps.
5. **Ready to Serve** – Describes the finished dish and serving suggestions.

This structure makes the recipe easier to follow while also adding storytelling to the cooking experience.

## Graduate Bonus Features

### 1. Kitchen Assistant

The Kitchen Assistant is a simulated AI assistant interface created with HTML and CSS. It provides predefined cooking questions and guided response cards for common situations, such as ingredient substitutions, reducing spice, and serving suggestions.

The feature uses semantic `<details>` and `<summary>` elements so users can open and close responses without JavaScript.

**AI concept:** The interface simulates how an AI cooking assistant could respond to common user questions.

**Design and accessibility checks:**
- The assistant cards remain readable on desktop and mobile layouts.
- Keyboard users can access and open the response cards.
- Visible focus styles help users identify the selected question.

### 2. What to Cook Next

The What to Cook Next section is a simulated recommendation engine that suggests additional recipes after viewing the current recipe.

Recommendation cards display dishes such as Fried Rice, Dumplings, and Kung Pao Chicken along with basic recipe information.

**AI concept:** The interface demonstrates how a recommendation system could suggest related recipes based on the user's current recipe.

**Design and accessibility checks:**
- The recommendation cards use a responsive CSS Grid layout.
- The three-column desktop layout changes to a single-column layout on smaller screens.
- Hover and focus states provide visual feedback when users interact with recommendation links.

Both graduate bonus features are front-end simulations built with HTML and CSS only. They do not use an external AI model, API, or JavaScript.
## Design and CSS Features

The website uses a reusable design system with CSS custom properties for colors, border radius, and transitions. This helps maintain a consistent visual style across all four pages.

The layout uses both modern CSS layout techniques:

- **CSS Flexbox** for navigation, ingredients, footer content, and other one-dimensional layouts.
- **CSS Grid** for recipe cards, team member cards, recommendation cards, and the Recipe Detail hero layout.

The project also includes several CSS animations and transitions:

- Hero entrance animation using `@keyframes`.
- Recipe card hover lift effect.
- Recipe image hover scale effect.
- Button hover transitions.
- Story Pack number animation.
- Kitchen Assistant card interaction.
- Recommendation and team card hover effects.

## Responsive Design

The website is designed to work across desktop, tablet, and mobile screen sizes.

Responsive behavior includes:

- Recipe cards changing from three columns to two columns and then one column.
- The hero layout stacking vertically on smaller screens.
- Navigation adapting for mobile screens.
- Recommendation cards changing to a single-column layout on smaller screens.
- Team member cards stacking vertically on mobile devices.
- Images using responsive sizing and `object-fit` where appropriate.

The final pages were manually tested at desktop, tablet, and mobile widths.

## Accessibility

Accessibility considerations include:

- Semantic HTML5 elements and logical page structure.
- Descriptive `alt` text for recipe and food images.
- Visible keyboard focus styles.
- `aria-current="page"` to identify the active navigation page.
- Form labels connected to their corresponding form fields.
- Readable text and background contrast.
- Keyboard-accessible Kitchen Assistant controls.
- A `prefers-reduced-motion` media query to reduce animations for users who prefer less motion.
## Testing and Quality Assurance

The final project was tested before submission to confirm that the pages, navigation, layouts, and styles work correctly.

Testing included:

- W3C HTML validation for all four HTML pages.
- W3C CSS validation for the final shared stylesheet.
- Desktop, tablet, and mobile responsive testing.
- Navigation and footer link testing.
- Image loading and relative path testing.
- Keyboard navigation and focus-state testing.
- Hover, transition, and animation testing.
- Kitchen Assistant interaction testing.
- Cross-page visual consistency checks.

The final HTML and CSS files passed W3C validation.

## Team Contributions

### Yalin Zhang

- Developed the Home page (`index.html`).
- Developed the Recipes page (`recipes.html`).
- Created the featured recipe and recipe card layouts.
- Implemented responsive layouts for the Home and Recipes pages.
- Added CSS transitions, hover effects, and the hero entrance animation.
- Added and organized the original food photography.
- Participated in final integration, testing, validation, and GitHub collaboration.

### Yunxue Wu

- Developed the Recipe Detail page (`recipe-detail.html`).
- Developed the About page (`about.html`).
- Implemented the five-part Story Pack.
- Created the Kitchen Assistant graduate bonus feature.
- Created the What to Cook Next recommendation interface.
- Developed the team and contact sections.
- Implemented responsive and interactive styles for the assigned pages.
- Participated in final integration, testing, validation, and GitHub collaboration.

## Assets and Credits

**Food Photography:** Original photos by Yalin Zhang.

The food images used in the project are original photographs and are stored locally in the `images` folder.

The website was created for CSC 6370 using HTML5 and CSS3.
## Project Structure

```text
chinese-home-kitchen/
├── images/
│   ├── hero-chinese-food.jpg
│   ├── dumplings.jpg
│   ├── tomato-egg.jpg
│   ├── mapo-tofu.jpg
│   ├── kung-pao-chicken.jpg
│   ├── fried-rice.jpg
│   └── braised-pork.jpg
├── qa/
├── index.html
├── recipes.html
├── recipe-detail.html
├── about.html
├── styles.css
└── README.md