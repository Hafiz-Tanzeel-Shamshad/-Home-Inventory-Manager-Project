# Home Inventory Manager

## Overview
Home Inventory Manager is a Java-based desktop application that helps you manage and track your home inventory items. It provides a graphical user interface for adding, deleting, and viewing items in your inventory, as well as features for searching, printing, and saving your inventory data.

## Features
- Add new inventory items with details such as location, serial number, purchase price, purchase date, store/website, and notes.
- Delete existing inventory items.
- Save inventory items to a file.
- Navigate through inventory items using "Previous" and "Next" buttons.
- Print the inventory list.
- Exit the application with a prompt to save changes.
- Search for items by the first letter of the item description.
- Attach photos to inventory items.

## Installation
1. **Download the repository:**
    ```sh
    git clone https://github.com/yourusername/home-inventory-manager.git
    ```
2. **Navigate to the project directory:**
    ```sh
    cd home-inventory-manager
    ```

3. **Compile the Java files:**
    ```sh
    javac -cp .:lib/* homeinventory/HomeInventory.java
    ```

4. **Run the application:**
    ```sh
    java -cp .:lib/* homeinventory.HomeInventory
    ```

## Dependencies
- `javax.swing` for the graphical user interface components.
- `com.toedter.calendar` for the date picker component.
- Java Development Kit (JDK) 8 or later.

## Usage
1. **Start the Application:**
   - Run the `HomeInventory` class to launch the application.

2. **Add a New Item:**
   - Click the "New" button on the toolbar.
   - Fill in the details for the new item.
   - Click the "Save" button to save the new item.

3. **Delete an Item:**
   - Navigate to the item you want to delete using the "Previous" and "Next" buttons.
   - Click the "Delete" button to remove the item.

4. **Search for an Item:**
   - Click the letter button corresponding to the first letter of the item description.

5. **Print the Inventory List:**
   - Click the "Print" button on the toolbar.

6. **Exit the Application:**
   - Click the "Exit" button on the toolbar.
   - You will be prompted to save any unsaved changes.

## File Structure
- `homeinventory/` - Contains the main application source files.
- `lib/` - Contains external libraries such as `com.toedter.calendar`.
- `inventory.txt` - The file where inventory data is saved and loaded from.

## Contributing
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`.
3. Make your changes and commit them: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature-branch`.
5. Submit a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Author
- Your Name - [yourusername](https://github.com/Hafiz-Tanzeel-Shamshad)

## Acknowledgments
- Thanks to the developers of the `com.toedter.calendar` library for the date picker component.
