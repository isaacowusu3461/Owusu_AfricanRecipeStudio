
# African Recipe Studio

## Project Information

**Name:** Isaac Owusu  
**Course:** CSC 6370 Web Programming  
**Institution:** Georgia State University  
**Project:** African Recipe Studio

## Project Overview

African Recipe Studio is a responsive website that allows users to explore different African dishes and learn how to prepare them. The website includes recipes from Ghana, Nigeria, Senegal, South Africa, and East Africa. Each recipe has its own page with background information, ingredients, cooking instructions, cooking time, and difficulty level. The website was developed using HTML and CSS, with a focus on responsive design, accessibility, and simple navigation.

## Website Features

- Homepage with featured African recipes
- Collection of six African dishes
- Individual recipe pages with cooking instructions
- CSS-only recipe filtering
- CSS-only recipe suggestion feature
- Responsive layout for desktop, tablet, and mobile devices
- Hover effects and animations
- Accessible navigation and keyboard controls
- About and Team pages

## Recipe Collection

The website includes the following recipes:

1. Ghanaian Jollof Rice
2. Waakye
3. Nigerian Egusi Soup
4. East African Chapati
5. Senegalese Chicken Yassa
6. South African Chakalaka

## Interactive Features

### Recipe Suggestion

The homepage includes a recipe suggestion feature where users can select the type of meal they want to prepare.

The available options are:

- Something Easy
- Rice Dish
- Soup or Stew

Based on the selected option, the website displays a recommended recipe.
This feature is a simulation implemented using HTML radio buttons and CSS selectors.

### Recipe Finder

The Recipes page allows users to filter recipes by category.
The available categories are:

- All Recipes
- Rice Dishes
- Soups and Stews
- Breads and Sides

The filtering works using CSS without JavaScript.

## Technologies Used

- HTML5
- CSS3
- CSS Grid
- Flexbox
- CSS Media Queries
- CSS Animations and Transitions
- Git and GitHub
- Visual Studio Code
- ClickUp for Kanban project management

## Project Structure

    AfricanRecipeStudio/
    ├── index.html
    ├── recipes.html
    ├── about.html
    ├── team.html
    ├── README.md
    ├── css/
    │   └── style.css
    ├── images/
    │   ├── jollof.jpg
    │   ├── waakye.jpg
    │   ├── egusi.jpg
    │   ├── chapati.jpg
    │   ├── yassa.jpg
    │   └── chakalaka.jpg
    |   └── kanban-backlog.png
    |   └── kanban-todo.png
    |
    ├── recipes/
    │   ├── jollof.html
    │   ├── waakye.html
    │   ├── egusi.html
    │   ├── chapati.html
    │   ├── yassa.html
    │   └── chakalaka.html
    └── docs/
        ├── testing.md
        └── development-journal.md

## How to Run the Website

1. Download or clone the project repository.
2. Open the project folder in Visual Studio Code.
3. Open `index.html` in a web browser.
4. Use the navigation menu to explore the website.

No additional installation or server is required.

## Responsive Design

The website uses CSS Grid and media queries to adjust the layout for different screen sizes. On desktop screens, the recipe collection displays three cards per row. On tablets, it displays two cards per row, and on mobile devices, it displays one card per row. The navigation, images, and page spacing also adjust to fit smaller screens.

## Accessibility

The website includes semantic HTML elements, descriptive image alt text, keyboard navigation, visible focus indicators, skip-to-content links, and current-page navigation indicators. It also supports reduced-motion preferences for users who prefer fewer animations.

## Project Management

I used a Kanban workflow in ClickUp to organize the project tasks and track development progress.

The board was organized into four stages:

- Backlog
- To Do
- In Progress
- Complete

Tasks were moved between the stages as development progressed. This helped me keep track of the remaining work and organize the implementation into smaller steps. Screenshots of the Kanban board are included in the development journal.

## Testing

I tested the website's navigation, recipe pages, interactive features, responsive layouts, and accessibility features. The tests passed, and the website worked as expected during the final review. The testing results are documented in `docs/testing.md`.

## AI Assistance

I used ChatGPT to assist with reviewing and debugging HTML and CSS code.


## Documentation

Additional documentation is available in the `docs` folder:

- `testing.md` - Functional, responsive, and accessibility testing
- `development-journal.md` - Development progress and Kanban workflow

## Author

Isaac Owusu  
M.S. Computer Science  
Georgia State University
