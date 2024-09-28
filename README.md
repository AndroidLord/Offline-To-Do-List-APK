# Offline To-Do List App

This is an offline-first to-do list application built using **Jetpack Compose** for the UI, **Room Database** for local data storage, and follows **MVVM** architecture with clean architecture principles. The app allows users to add, edit, delete, and reorder tasks, ensuring a smooth and efficient user experience.

## Features

- **Add Task**: Users can add new tasks to the list.
- **Edit Task**: Users can modify existing tasks.
- **Delete Task**: Users can delete tasks from the list.
- **Reorder Tasks**: Users can drag and reorder tasks with changes reflected both in the UI and saved to the database.
- **Display Tasks with Pagination**: Tasks are displayed with pagination to efficiently handle large datasets.

## Tech Stack

- **Jetpack Compose**: For building dynamic and reactive UI.
- **Room Database**: For offline storage and data persistence.
- **MVVM Architecture**: To separate concerns and ensure maintainable code.
- **Repository Pattern**: For managing data access and business logic.

## Bonus Implementations

- Smooth drag-and-drop functionality for task reordering.
- Proper handling of edge cases like empty list states.
- Efficient management of large datasets with pagination.

## How to Run

- Install the APK on an Android device.
- Launch the app and start managing your tasks offline.

## Additional Information

- The app uses clean architecture principles, ensuring a separation of concerns between UI, data, and business logic.
- All data is stored locally on the device using Room Database, making it an offline-first app.

Feel free to explore the app and enjoy seamless task management!
