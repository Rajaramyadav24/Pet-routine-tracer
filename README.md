# Pet Routine Tracker

The Pet Routine Tracker is a comprehensive, client-side web application designed to help pet owners manage their pets' daily activities, health records, routines, and view statistics about their care. All data is stored locally in your web browser's localStorage.

## Features

*   **Pet Management:** Add and manage multiple pets, including their name, type, breed, age, weight, and photos.
*   **Activity Logging:** Log various activities for your pets, such as feeding, walks, medication, grooming, play time, and training. Activities can include dates, times, durations, notes, and photos.
*   **Health Records:** Keep track of health-related events like vaccinations, checkups, illnesses, weight records, and other medical notes, complete with dates, descriptions, veterinarian details, and photos.
*   **Routines & Schedules:** Set up recurring routines for activities like feeding or medication, specifying frequency and time. View upcoming tasks based on these routines.
*   **Statistics Dashboard:** Visualize your pets' activity trends, distribution, health scores, and other metrics on a modern analytics dashboard. Includes charts for activity distribution, progress trends, pet comparisons, and an activity heatmap.
*   **Data Export:** Export all your pet data (pets, activities, health records, routines) as a JSON file for backup.
*   **Dark Mode (Partial Implementation):**
    *   A toggle button (sun/moon icon) is available in the header to switch between light and dark themes.
    *   The JavaScript logic for theme selection, switching, and saving your preference in localStorage is implemented.
    *   Basic styling for dark mode has been applied to global elements (body, header, navigation) and some cards and buttons.
    *   **Limitation:** Comprehensive dark mode styling across all components (especially modals, forms, and some dynamically generated content) could not be completed due to technical difficulties encountered with the available tooling for modifying the HTML structure. Some areas of the application may not display optimally in dark mode.
*   **Responsive Design Foundation:**
    *   The application is built with Tailwind CSS, a utility-first CSS framework that is inherently designed for creating responsive layouts.
    *   While the application should adapt to different screen sizes, further specific fine-tuning and testing for optimal display on all devices (mobile, tablet, desktop) could be a future enhancement.

## How to Use

1.  Download or clone the `pet routine tarcker.html` file.
2.  Open the `pet routine tarcker.html` file in a modern web browser (e.g., Chrome, Firefox, Safari, Edge).
3.  All data you enter will be saved in your browser's local storage.

## Contributing

Currently, contributions are not actively being sought due to the tooling limitations mentioned above, which make complex code modifications challenging.
