# Test-Automation-Simulation
Software Test Automation Engineer Simulation

Installation
## install all dependencies from the root directory
npm install

## Running from the CLI
npm run testProj2

## Documentation
##    Page Objects
      o	AuthenticationPage.js: contains locators used to initiate account creation and login user.
      o	BasePage.js: contains common locators or functions that can be used on multiple pages of the application.
      o	CreateAccountPage.js: contains locators for creating a user account. 
      o	DashboadPage.js: contains the locators on the main page of the application.
      o	MyAccountPage.js: contains locators to manage personal information, order and navigate away from My Account page.
      o	ShoppingCartPage.js:  contains locators used for automation the Shopping Cart and Checkout workflow
##	Test Files
      o	account-create.spec.js: This contains the test steps for creating a user.
      o	login.spec.js: contains login test scenarios.
      o	Purchase-items.spec.js: contains the test steps for shopping cart and checkout workflow.
      o	Search-items.spec.js: contains a basic test step for searching for items on the website.
##	Data
      o	data.json: This file is used to store data used within the test.

