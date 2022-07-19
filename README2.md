# fast_food_feud
### Application Features
#### CORE FEATURES
- [x] Displays the title, tagline description, data source, and instructions in the Header and Instructions component
- [x] Categories are displayed in a column and restaurants are displayed in a row.
- [x] Chip component updates based on the restaurant and category selected by the user.
- [x] When a menu item is selected, the NutritionalLabel component is displayed with the nutritional facts of the item.
#### STRETCH FEATURES
- [ ] Render different instructions messages depending on state
- [ ] Add additional onClick handlers to Chip
- [ ] Break sections of the App.jsx file into their own components (CategoryColumn.jsx, RestaurantsRow.jsx, MenuDisplay.jsx, and DataSource.jsx).
#### MY NOTES
- .jsx signifies we are writing React code, but React code is essentially compiled to JavaScript
- The app gets rendered into the index.html file from main.jsx, and App.jsx has the bulk of the functionality
- Components are functions that return HTML code, take in a props arguments that customizes what is rendered into the JSX component
- Can think of props kind of like a list of parameters of variable length??
- Props are useful because we can reuse some code while allowing it to be customized
- Props = component data that doesn't change
- useState hook:
    - returns an array containing the state value and state setter function
    - always use the setter function if we want to change the state (can't change it directly)
    - important thing is that it remembers the past state (keep a record of what's changed after the user interacts with the App)
    - State = component data that does change 

