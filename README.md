⚠️ Link to the final project: [DEMO](https://fantantonio.github.io/e-plantShopping/)

# Final Project Overview

For your final project, you will create the front end of a "Paradise Nursery" shopping application. The application interface will allow you to browse a variety of houseplants and add them to a shopping cart. The shopping cart feature lets you see all your items and their total cost. Your shopping cart should also allow you to adjust the number of items in the cart before checkout.

Completing the practice project will help you with the final project. We designed it so that many of the components, code, and skills for that project can be transferred to this peer-reviewed project with some updates.

Your application should have three pages: a landing page, a product listing page, and a shopping cart page. See the lab for details on the specific functionality requirements on each page. The product walkthrough video also demonstrates how your completed project should look and behave.

In this final project, you will create a shopping cart application for an online plant shop which offers a variety of house plants.

The Paradise Nursery shopping cart features will include:

- A Landing page with a button linking to the product listing page
- A navigation bar with links to the landing, product listing, and shopping cart pages
- A card for each plant that showcases the different plants along with their images, name, description, cost and an **Add to cart** button.
- A minimum of two sections describing the plants in that section. For example, "Aromatic Plants" and "Medicinal Plants".
- A cart page which displays the products in the cart.
- The cart should have a card for each type of plant in the cart. Each card should have the thumbnail, the unit cost, the cost for all of the plants of that type and buttons to increase and decrease the quantity along with Delete button.
- A **Continue Shopping** and **Checkout** buttons

You will implement the knowledge and skills you gained from working on the practice project to handle dynamic functionalities, like the show cart quantity in the icon on the navbar and updating the cost of all of the items in the cart when the user updates the number of items.

## Landing page

The landing page should have the following elements:

- A background image
- A paragraph about the company
- The company name
- A **Get Started** button linking to the product page

The product listing page should have at least six houseplants for sale, organized into three or more categories. Each plant should have the following details about it:

- A thumbnail image
- Plant name
- Price
- An **Add to Cart** button

## Product listing page

The product listing and shopping cart pages should have a header. The header should have a shopping cart icon with a number that updates dynamically, displaying the total number of items in the cart. The header should also contain navigation to either of the other pages, depending on which page you are on.

## Shopping cart page

The shopping cart page displays all the details about the items in it. It should prominently display the total number of plants in the cart, the total cost of all items in the cart, a continue shopping button, and a checkout button.

On this page, you should be able to see each type of plant in the shopping cart, including its thumbnail and name. You should also display its unit price and the total of all the items in the cart. You should provide an increase or decrease button to change the number of that plant type in the cart, which also updates the shopping cart icon in the header and the total number of items in the cart. Finally, you should also include a delete button for each type of plant in the cart.

You will need to store your project code in a GitHub repository with public access. You will submit a link to this repository so a peer can review your work.

## Learning objectives

After completing this lab, you will be able to:

- React Components: Create functional React components using component composition and nesting.
- State Management with Hooks: Implement React Hooks, specifically the useState and useEffect hooks. You will manage component-level state using hooks to control the visibility of elements.
- Redux Integration: Integrate Redux within an application using Redux concepts like actions, reducers, and the store.
- Rendering Dynamic Data: Dynamically render data fetched from an array of objects into the UI. You will map over arrays to generate lists of components.
- Handling Events and Conditional Rendering: Handle user events such as button selection and trigger corresponding actions.

## Grading Criteria Overview

50 points, 19 tasks

### GitHub (6 points, 2 tasks)

GitHub repository public URL: 2 points

✅ Redux-related files and code: 4 points

### Landing page (5 points, 4 tasks)

✅ Background image: 1 point

✅ Paragraph about the company: 1 point

✅ Company name: 1 point

✅ Get Started button linking to the product listing page: 2 points

### Product listing page (9 points, 3 tasks)

✅ Six unique houseplants for sale, each displaying thumbnail, name, and price: 2 points

✅ Group the plants into at least three categories on the page: 1 point

✅ An Add to Cart button for each plant, each with the following behavior: 6 points

✅ After selecting it, the shopping cart icon increases by one.

✅ After selecting it, the button becomes disabled.

✅ After selecting it, the appropriate plant gets added to the shopping cart.

### Header (7 points, 3 tasks)

✅ Displays on both the product listing page and shopping cart page 2 points

✅ A shopping cart icon with a value that displays the total number of items in the cart: 3 points

✅ Navigation to either of the other pages: 2 points

### Shopping cart page (23 points, 8 tasks)

✅ The total number of plants in the cart: 2 points

✅ The total cost of all items in the cart: 2 points

✅ Each plant type in the cart displays a thumbnail, name, and unit price: 6 points

✅ Increase button for each plant type in the cart that increments the number of items in the cart by one each time it's clicked and updates all appropriate values: 4 points

✅ Decrease button for each plant type in the cart that decrements the number of items in the cart by one each time it's clicked and updates all appropriate values: 4 points

✅ A delete button: 2 points

✅ A checkout button (displays the message “Coming Soon” or similar): 1 point

✅ A continue shopping button that links to the product listing page: 2 points
