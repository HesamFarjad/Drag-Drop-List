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



<img width="1440" alt="Screenshot 2024-05-27 at 15 43 01" src="https://github.com/HesamFarjad/Drag-Drop-List/assets/81914229/47efa042-1dfe-4a2b-a7ea-4a339ed20841">
<img width="1440" alt="Screenshot 2024-05-27 at 15 42 56" src="https://github.com/HesamFarjad/Drag-Drop-List/assets/81914229/adcafd9e-ea79-4483-9466-8e9b8422b50d">
<img width="1440" alt="Screenshot 2024-05-27 at 15 42 48" src="https://github.com/HesamFarjad/Drag-Drop-List/assets/81914229/9cb41b43-e056-4428-af62-30eac64aab24">
<img width="1440" alt="Screenshot 2024-05-27 at 15 42 39" src="https://github.com/HesamFarjad/Drag-Drop-List/assets/81914229/81642068-4080-4eff-95c7-8ad8dd312ec0">
<img width="1440" alt="Screenshot 2024-05-27 at 15 41 58" src="https://github.com/HesamFarjad/Drag-Drop-List/assets/81914229/592d9d25-0b30-408e-8c1c-535a5051db15">
