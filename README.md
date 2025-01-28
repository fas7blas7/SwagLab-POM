# SwagLabsPOM.csproj

## Overview
**SwagLabsPOM.csproj** is a Page Object Model (POM) structured project designed for testing the Swag Labs web application. It follows best practices for UI test automation, ensuring maintainability and scalability.

## Project Structure
The project is organized into two main folders:

### 1. **Pages**
This folder contains the page object classes that represent different sections of the application:
- **BasePage** - A base class containing shared functionality for all pages.
- **CartPage** - Represents the cart functionality and interactions.
- **CheckoutPage** - Handles interactions with the checkout process.
- **HiddenMenuPage** - Manages interactions with the hidden menu feature.
- **InventoryPage** - Represents the product inventory page.
- **LoginPage** - Handles interactions with the login functionality.

### 2. **Tests**
This folder contains the test classes that validate the functionality of the pages:
- **BaseTests** - A base test class with shared setup and teardown logic.
- **CartPageTests** - Tests for the cart page functionality.
- **CheckoutPageTests** - Tests for the checkout process.
- **HiddenMenuPageTests** - Tests for the hidden menu feature.
- **InventoryPageTests** - Tests for the product inventory page.
- **LoginPageTests** - Tests for the login functionality.

## Technologies Used
- **C#**
- **Selenium WebDriver**
- **NUnit/xUnit** (or another testing framework if applicable)

## Setup & Execution
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/SwagLabsPOM.git
   ```
2. Navigate to the project directory:
   ```sh
   cd SwagLabsPOM
   ```
3. Restore dependencies:
   ```sh
   dotnet restore
   ```
4. Run the tests:
   ```sh
   dotnet test
   ```
