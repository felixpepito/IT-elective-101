<!-- ------------------------------------------------------------------------------------ -->
<!-- Login and Register Forms
There are two tabs, one for logging in and one for registering. You can switch between them by clicking the buttons.
Login Form: Enter your email and password. There's an eye icon to show or hide the password.
Register Form: Fill in your username, email, and password to create an account. After registering, you'll be switched back to the login tab.
JavaScript Functions:
openForm(): Shows the selected form (login or register) and hides the other.
togglePassword(): to show or hide the password in the input field.
Form Submission:
Login: Checks if the entered credentials match the stored data and then redirects to another page if they do.
Register: Saves the new user data and switches to the login form.-->
<!-- ------------------------------------------------------------------------------------ -->
<!-- ------------------------------------------------------------------------------------ -->
<!-- add-item
 users can add a new item to a list. Here's a breakdown of how it works and how users can use it:

Header Section:
There's a button (three horizontal bars) that users can click to open or close a sidebar. The sidebar is a menu on the side of the page.

Form to Add an Item:
Product Name: Type the name of the product.
Brand: Type the brand of the product.
Price: Type the price of the product.
Weight/Volume: Type the weight or volume of the product.
Quantity: Type how many units of the product you have.
Store: Type the store where the product is available.
Category: Choose a category for the product from a dropdown list (Vegetables, Fruits, Meals).
Image: Upload an image of the product if you have one.
Add to List Button: Click this button to add the item to the list.

Bottom Navigation:
Three links at the bottom of the page:

Add Item: Goes to this page to add another item.

Shop: Goes to a shop page.

List: Goes to a page with a list of items.

Sidebar Section:
Close Button: Click this to close the sidebar.
Logout Link: Click this to log out and go back to the home page.

JavaScript Functions:
toggleSidebar(): Opens or closes the sidebar when the button is clicked.

closeSidebar(): Closes the sidebar.

Form Submission:
When the form is submitted, it prevents the default behavior (which is usually to reload the page).
It collects the information entered in the form and processes the image if uploaded.
It creates an object with all the form data.
It saves this object in the browser’s local storage so it can be used later.
It shows a success notification with SweetAlert and then reloads the page to reset the form. -->
<!-- ------------------------------------------------------------------------------------ -->
<!-- ------------------------------------------------------------------------------------ -->

<!-- 
Sidebar:
we have  three-bar icon at the top to open or close the sidebar.
Inside the sidebar, you can log out by clicking the "Log out" link.
Search and Cart:
Use the search bar at the top to find items by typing keywords.
the cart icon to open or close the cart.

Categories:
 on category links (Vegetables, Fruits and meals) to filter items based on the selected category.

Sorting:
 dropdown menu to sort items by options like Price or Product Name.

Viewing Items:
Browse the displayed items. Each item has a checkbox, an image, and a button to add it to your cart.

Adding to Cart:
Click the "Add to Cart" button on an item to add it to your shopping cart.

Cart Management:
In the cart section, you can see items you’ve added, adjust quantities, and remove items.
Click “Buy Now” to proceed with purchasing.

Cart Item Count:
The number on the cart icon shows how many items are currently in your cart. -->

<!-- ------------------------------------------------------------------------------------ -->
<!-- ------------------------------------------------------------------------------------ -->

<!-- 
Sidebar: Use the three-bar icon at the top to open or close the sidebar. It provides links to "Add Item" and "Shop" pages.

Search Bar: Enter text to search for items. The list updates automatically based on your search.

Categories: Click on category links ( Vegetables, Fruits) to filter the items by their category.

Item Display: Items are shown with details like name, brand, price, etc.
Features:
Edit Items:
if clickyou the "Edit" button (pencil icon) next to an item.
A popup will appear allowing you to update item details.
You can also upload a new image for the item.
Changes are saved after confirming in the popup.

Remove Items:
if you click the "Remove" button (trash can icon) next to an item.
A confirmation popup will appear. Confirm the deletion to remove the item.

Implementation Details:
SweetAlert2: Used for better-looking alerts and prompts (editing and removing items).

LocalStorage: Stores items so that they persist between page reloads.
Usage:
To Add/Edit Items: Use the sidebar link or edit buttons next to items.
To Search/Filter Items: Use the search bar and category links.
To Remove Items: Use the remove button next to each item.

<!-- ------------------------------------------------------------------------------------ -->
<!-- ------------------------------------------------------------------------------------ -->