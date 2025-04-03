General Features
Font: Arial

Responsive Layout: The web app should be fully responsive, adapting to screen size changes, and ensuring all elements are clearly visible and accessible on both PC and mobile devices.

Top Controls
Add Button

Function: Increases the number of instances displayed on the screen.

Action: Adds one new instance.

Subtract Button

Function: Decreases the number of instances displayed.

Action: Removes one instance from the screen.

Initial Load

When the page is loaded, the app should display one instance by default.

Background Canvas

The background should be a dynamic fullscreen canvas.

Function: Allows users to drag and arrange instances freely across the canvas.

Behavior:

Instances snap into adaptable rows and columns for better organization.

Instances are resizable by the user through drag-to-resize functionality.

The layout adapts automatically to screen size adjustments.

Instance Structure
Each instance consists of two distinct sets, with each set containing two rows of 6 cells. These cells include both text and numerical input fields:

Text Input Rows (Top Rows)

Set 1 (6 cells):

Labels: STR, DEX, CON, INT, WIS, CHA.

Set 2 (6 cells):

Labels: HP, AC, DC, PP, Ammo, Charges.

These rows will accept textual input and can be edited by the user.

Numerical Input Rows (Bottom Rows)

Spinner:

Numeric spinners are attached to each of the numerical fields (ranging from 0 to 99).

If non-numerical input is entered in a numerical field, the value should default to 0.

The numerical input fields are centrally aligned for a clean appearance.

Spell Slots Table

Layout:

A collapsible table with two rows:

First Row: Labels 1 through 9 (representing spell slot levels).

Second Row: Numeric input for spell slots per level.

Behavior: The table is collapsible to save screen space when not in use.

Instance Controls
Generate Button

Function: Generates four random values.

Process:

The app should generate four random numbers.

Drop the lowest of the four values.

Add the remaining three values and display the sum across the top numeric row.

Hover Effect: When hovering over a generated numerical cell, display the four original values in a hover box. Format:

Example: "5, 4, 3, (2)" — the dropped value is shown in parentheses.

Reset Button

Function: Resets all text and numerical input fields back to their default state.

Color Theme Menu
Dropdown Menu

Purpose: Allows the user to select from 12 predefined color themes.

Available Themes:

White, Gray, Black, Brown, Red, Orange, Yellow, Green, Blue, Indigo, Violet, Pink.

Default Theme: White (high-contrast white and black color scheme).

Cycle Theme Button

A small square button placed next to the dropdown menu.

Function: Cycles through the color themes in order when clicked, applying each theme to the instance.

User Input and Customization
Name Input Field

Label: "Name:"

Position: Located at the top of the instance ghost.

Font: Large font size to make it prominent.

Width: The input field should match the width of the cell rows.

Multi-Line Text Fields (Actions, Spells, Inventory, Notes)

Position: Placed at the bottom of the instance ghost.

Labels:

Actions

Spells

Inventory

Notes

Font: Smaller than the name input field for visual distinction.

Width: Each text field should match the width of the cell rows.

Behavior: These fields are draggable and resizable, allowing the user to adjust their positions and size as needed.

Interactive Features
Draggable Instances

Each instance can be dragged and repositioned on the canvas.

The instances will snap into place when arranged within rows and columns.

Resizable Instances

Each instance can be resized by dragging its edges, allowing users to adjust the layout as needed.

Collapsible Tables

All tables, such as the Spell Slots table, are collapsible to save space when not needed.

Summary of Functionality
The web app provides a flexible and interactive environment where users can manage and customize instances, displaying them in an adaptable, resizable layout.

The "Add" and "Subtract" buttons allow for dynamic scaling of instances, while the various input fields let users modify their data directly.

The color theme menu and interactive controls such as the "Generate" and "Reset" buttons provide further customization and functionality.

The app's layout and structure should be easy to use and visually organized, ensuring an optimal user experience across different devices.
