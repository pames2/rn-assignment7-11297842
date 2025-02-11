# Pamela Boateng

## Design Choices

### Navigating
Using React Navigation, I created a hybrid drawer and stack navigation system. This option offers:

1. The drawer provides simple access to the primary areas (Products and Cart).
2. Stack navigation allows for fluid movement between linked screens (such as the product list and product details).
3. A uniform user interface with a unique header picture and cart symbol on every screen.

### User Interface Elements
- Custom Header: For brand consistency, an image takes the place of word titles.
- CartIcon: A dynamic icon that indicates how many things are in the cart at any one time.
- CustomDrawerContent: Adds a user name to the top of the drawer to make it more unique.

### State Administration
To manage the state of the shopping cart, we make use of React's Context API. This makes it possible to: - Access cart info globally across all components.
• Cart operations are managed centrally.

## Screenshots:

![Home Screen](HomeScreen.jpg)

![Drawer Menu](Drawer.jpg)

![Product Detail](pd.jpg)

![Cart](cart.jpg)