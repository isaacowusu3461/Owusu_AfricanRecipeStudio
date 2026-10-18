
# African Recipe Studio - Testing Report

**Student:** Isaac Owusu  
**Course:** CSC 6370 Web Programming  
**Project:** African Recipe Studio

## 1. Testing Overview

I tested the African Recipe Studio website to make sure the pages, navigation links, images, and interactive features worked correctly. I also checked the responsive layout and accessibility features to make sure the website was usable on different screen sizes. The tests I completed passed, and I did not encounter any remaining functional issues.

## 2. Functional Testing

| Test | Expected Result | Result |
|---|---|---|
| Homepage | Homepage loads correctly | Pass |
| Navigation | All navigation links open the correct pages | Pass |
| Recipe collection | All six recipes are displayed | Pass |
| Recipe detail pages | Each recipe opens with the correct information | Pass |
| Recipe images | All JPG images load correctly | Pass |
| Recipe suggestion | Selected option displays the matching suggestion | Pass |
| Recipe finder | Category filters display the correct recipes | Pass |
| Back to Recipes | Link returns to the recipe collection | Pass |
| Footer | Footer stays at the bottom on short pages | Pass |

## 3. Responsive Design Testing

| Screen Size | Expected Result | Result |
|---|---|---|
| Desktop | Three recipe cards per row | Pass |
| Tablet | Two recipe cards per row | Pass |
| Mobile | One recipe card per row | Pass |
| Small mobile screen | Content fits without horizontal overflow | Pass |

I checked the layout at different screen sizes. The recipe cards adjusted correctly, and the navigation and images remained readable. I also checked the footer positioning on pages with less content. After updating the CSS layout, the footer stayed at the bottom of the screen.

## 4. Interactive Feature Testing

### Recipe Suggestion

I tested the three options on the homepage.

| Selected Option | Expected Recipe | Result |
|---|---|---|
| Something Easy | East African Chapati | Pass |
| Rice Dish | Ghanaian Jollof Rice | Pass |
| Soup or Stew | Nigerian Egusi Soup | Pass |

Each option displayed the expected recipe suggestion.

### Recipe Finder

I tested the category filters on the Recipes page.

| Filter | Expected Result | Result |
|---|---|---|
| All Recipes | Displays all six recipes | Pass |
| Rice Dishes | Displays Jollof Rice and Waakye | Pass |
| Soups and Stews | Displays Egusi Soup and Chicken Yassa | Pass |
| Breads and Sides | Displays Chapati and Chakalaka | Pass |

The filters worked as expected without JavaScript.

## 5. Accessibility Testing

| Test | Expected Result | Result |
|---|---|---|
| Keyboard navigation | Links and controls can be accessed using the keyboard | Pass |
| Skip link | Skip-to-content link appears when focused | Pass |
| Current page indicator | Active navigation link is highlighted | Pass |
| Image alt text | Recipe images include descriptive text | Pass |
| Focus indicators | Keyboard focus is visible | Pass |
| Reduced motion | Animations are disabled when reduced motion is requested | Pass |

The accessibility features worked during testing. I was able to navigate the website using the keyboard and interact with the recipe filters.

## 6. Issues Found and Fixes

### Footer Positioning

One issue I noticed was that the footer appeared above the bottom of the screen on pages with less content. I fixed this by updating the CSS to use Flexbox on the body and allowing the main content to take up the remaining vertical space. After the change, the footer stayed at the bottom on shorter pages without covering the content on longer pages.

### Responsive Layout

I checked the recipe grid on different screen sizes to make sure the cards were displayed correctly. The media queries adjusted the number of columns depending on the available screen width.

### Interactive Features

I tested the recipe suggestions and category filters to confirm that the correct content appeared when each option was selected. Both features worked as expected.

## 7. Final Testing Summary

After completing the final tests, the website worked as expected. All pages loaded correctly, the navigation links worked, and the recipe images displayed properly. The responsive layout, CSS interactions, and accessibility features also passed the checks I completed. The footer positioning issue was fixed, and I did not find any remaining problems during the final review.
