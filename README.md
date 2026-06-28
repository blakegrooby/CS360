# CS360
CS-360-12894-M01 Mobile Architect &amp; Programming


App Summary

This app was designed as a simple inventory management tool called StockWise Inventory. The main goal was to let a user create an account, log in, and manage inventory items in one place. The app was built to address the need for a straightforward way to track item names, quantities, locations, and low-stock limits without making the process confusing or overloaded with extra features. It also supports optional SMS alerts for low inventory, which helps users respond faster when stock reaches a set threshold.

Screens and Features

The app needed a login screen, an inventory screen, and an add or update item screen to support user needs. The login screen lets new users create an account and returning users sign in. The inventory screen displays saved records in a grid-style layout so users can read their stored data clearly, and it also supports deleting or selecting an item for editing. The add or update screen lets users save item details and manage SMS alert settings.
My UI designs kept users in mind by focusing on clarity, readable labels, simple navigation, and limited actions per screen. I tried to avoid clutter and make each screen serve one main purpose. I think the designs were successful because the app is easy to follow, and the user can move through the main tasks without needing extra instructions.

Coding Process

I approached coding by building the app in smaller parts instead of trying to complete everything at once. I first focused on the screen structure, then added the SQLite database, then connected login and CRUD features, and finally added SMS permission handling. I used separation of responsibilities across activities and helper classes so the project stayed more organized. I also used clear naming and comments to make the code easier to read.
These strategies can be used in the future for larger projects too. Breaking a problem into smaller steps makes debugging easier and helps keep the code manageable over time.

Testing

I tested the app by building it often, checking for compile errors, and reviewing whether each main feature worked as expected. I also checked the login flow, account creation, database saving, add, update, delete, and SMS permission behavior. This process is important because code that looks correct is not always functional once all the parts are connected. Testing revealed small issues during development and helped confirm that the app 
could actually perform the required tasks reliably.

Innovation and Challenges

One challenge was connecting several required features into one working app without making it overly complicated. I had to combine persistent login storage, inventory CRUD operations, and optional SMS alerts in a way that still felt simple for the user. I had to think carefully about how permission denial should affect the rest of the app, and I made sure the app still functioned even if SMS access was denied. That was one area where I had to be flexible and solve the problem in a practical way.

Strongest Area

The area where I was most successful was the database-driven inventory system. I think this part shows my knowledge best because it includes account storage, persistent data, reading records back to the screen, and allowing the user to create, update, and delete entries. That part brought together both the interface side and the backend logic side of the app, and it shows the strongest overall growth in my mobile development skills.
