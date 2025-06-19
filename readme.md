# Bash Shell Menu Project

This project implements a menu-driven interface using Bash shell scripts. It provides a modular structure for creating, using, and managing menu options and submenus, making it easy to extend and maintain.

## Project Structure

- `entryPoint` - The main entry point script to start the menu system.
- `Menu/` - Contains all menu-related scripts and submenus.
  - `create`, `drop`, `mainMenu`, `use` - Scripts for main menu operations.
  - `submenu/` - Contains scripts for submenu operations:
    - `create`, `createHelperFunctions`, `delete`, `drop`, `insert`, `select`, `submenu`, `update`, `validdatorFunction`

## Features
- Modular menu and submenu system
- Easy to add, update, or remove menu options
- Helper functions for validation and database-like operations

## Getting Started
1. Make sure you have Bash installed on your system.
2. Run the `entryPoint` script to start the menu:
   ```bash
   bash entryPoint
   ```
3. Follow the on-screen prompts to navigate the menu and perform actions.

## Customization
- To add new menu options, create new scripts in the `Menu/` or `Menu/submenu/` directories.
- Update the main menu or submenu scripts to include your new options.

## License
This project is for educational purposes.
