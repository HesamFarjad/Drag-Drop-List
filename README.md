# Drag-Drop-List
It includes TypeScript interfaces, classes, and decorators to manage the project's state, validate inputs, and handle drag-and-drop operations.


This TypeScript code is a comprehensive example of a drag-and-drop project management application. It uses TypeScript's powerful type-checking and object-oriented features to create a robust and scalable codebase.
* Interfaces: Define the structure for draggable items and drag targets.
* Enums: Enumerate project statuses.
* Classes: Handle project creation, state management, validation, and UI rendering.
    * ProjectState: A singleton class managing the state of all projects.
    * Validation: Ensures user inputs are valid before creating projects.
    * Autobind Decorator: Binds class methods to the correct context.
    * Component Base Class: Provides a blueprint for creating UI components.
    * ProjectItem: Represents individual project items, implementing drag-and-drop functionality.
    * ProjectList: Manages lists of projects, updating the UI based on the state.
    * ProjectInput: Manages the user input form, validating and adding new projects.
* Instantiation: Sets up the application by creating instances of the input form and project lists for active and finished projects.


<img width="1440" alt="Screenshot 2024-05-27 at 15 43 01" src="https://github.com/HesamFarjad/Drag-Drop-List/assets/81914229/18bb1db5-37f0-4f8e-8b65-3f843d403d4b">
<img width="1440" alt="Screenshot 2024-05-27 at 15 42 56" src="https://github.com/HesamFarjad/Drag-Drop-List/assets/81914229/be3458f5-ccd4-4bee-9857-9a4ed232fcbd">
<img width="1440" alt="Screenshot 2024-05-27 at 15 42 48" src="https://github.com/HesamFarjad/Drag-Drop-List/assets/81914229/9c69bdce-7a00-4e43-bf1e-d6b8ac8db3fd">
<img width="1440" alt="Screenshot 2024-05-27 at 15 42 39" src="https://github.com/HesamFarjad/Drag-Drop-List/assets/81914229/227ec0df-42c6-4b29-9543-b8cd6be4445c">
<img width="1440" alt="Screenshot 2024-05-27 at 15 41 58" src="https://github.com/HesamFarjad/Drag-Drop-List/assets/81914229/10cccc66-2c9a-4d21-ae3f-6292223d169f">
