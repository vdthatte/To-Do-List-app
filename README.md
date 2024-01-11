# Task Manager iOS App

![App Preview](https://login.trace.zip/storage/v1/object/public/trace/19f2d81f-a93e-404c-afde-0d329499d711)

This is a simple Task Manager iOS app built using SwiftUI. The app allows users to create, edit, and delete tasks, as well as mark them as completed. This project was built using [Trace AI](https://trace.zip) and can be demoed at [https://trace.zip/c/19f2d81f-a93e-404c-afde-0d329499d711](https://trace.zip/c/19f2d81f-a93e-404c-afde-0d329499d711).

## Features

- Create new tasks
- Edit task titles
- Mark tasks as completed
- Delete tasks

## Building the App

To build the app, follow these steps:

1. Clone the repository to your local machine.
2. Open the Xcode project file.
3. Build and run the app on an iOS simulator or a physical device.

## App Structure

The app consists of a single `ContentView` which displays a list of tasks. Each task is represented by a `Task` struct, which has an `id`, `title`, and `isCompleted` property.

The `ContentView` has a `NavigationView` that contains a `List` of tasks. Each task is displayed in an `HStack` with a button to toggle its completion status and a `TextField` to edit its title.

The `NavigationView` also has a toolbar with a button to add new tasks.

## Adding and Deleting Tasks

To add a new task, tap the "+" button in the toolbar. This will create a new `Task` object with a default title and completion status of `false`. The new task will be appended to the `tasks` array.

To delete a task, swipe left on the task in the list and tap the "Delete" button. This will remove the task from the `tasks` array.

## Previewing the App

To preview the app, open the `ContentView_Previews` struct in the Xcode project. This will display a live preview of the app in the Xcode canvas.