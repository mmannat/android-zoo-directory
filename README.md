Android Zoo Directory

This project is a simple Android application that displays a list of animals and allows users to view detailed information for each one. It was built to practice structured UI design, list-detail navigation, and clean interaction handling in Android.

What the app does:

- Displays a scrollable list of animals
- Each item shows a thumbnail image and name
- Tapping an animal opens a detailed view screen
- Includes a conditional warning dialog for a specific edge-case interaction

Technical concepts used:

- RecyclerView for dynamic list rendering
- Custom Adapter implementation
- Activity navigation (List → Detail screen)
- Intent data passing between activities
- AlertDialog handling
- Basic Android lifecycle awareness

Project structure:

- Model class representing each animal
- Adapter class managing list rendering
- Separate activities for list and detail screens
- Layout files defined in XML
- Gradle-based Android project configuration

Tech stack:

Kotlin / Java (depending on implementation)  
Android SDK  
Gradle build system  

Why this project matters:

This app demonstrates foundational Android development patterns such as structured UI composition, event-driven interaction, navigation flow control, and reusable adapter logic. It reflects early-stage mobile architecture using proper Android project structure and build configuration.

How to run:

1. Clone the repository  
2. Open the project in Android Studio  
3. Sync Gradle dependencies  
4. Run on emulator or physical device  
