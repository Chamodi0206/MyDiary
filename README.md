# MyDiary Android App

**MyDiary** is an Android application designed to allow users to create, view, and edit their personal diary entries. The app allows users to manage their thoughts, experiences, and images with ease. Each diary entry includes a title, description, date, and an optional image.

---

## Features

- **Create Diary Entries:** Users can add new diary entries with a title, description, and image.
- **View Diary Entries:** Users can view all their saved diary entries in a list.
- **Edit Diary Entries:** Users can modify existing diary entries.
- **Save Preferences:** Users can set and save their username for personalization.
- **Image Support:** Attach images to diary entries.

---

## Technologies Used

The following technologies and frameworks are used in the development of the app:

- **Programming Language:**  
  - **Java** for Android application development.

- **Android SDK:**  
  - For building the Android application and accessing Android system features.
  
- **SQLite Database:**  
  - For local data storage and management of diary entries.

- **SharedPreferences:**  
  - Used for storing user preferences such as the username.

- **Glide:**  
  - A powerful image loading library to load images from URIs into ImageViews efficiently.

- **Android Views:**  
  - Various UI components like `TextView`, `Button`, `EditText`, `ImageView`, etc., to build the user interface.

- **DatePickerDialog:**  
  - To allow the user to select a date from a calendar.

- **Intent & Activity Lifecycle:**  
  - Used for navigation between different activities and managing app flow.

---

## App Structure

The app follows a **Model-View-Controller (MVC)** architecture. Here's an overview of the main components:

### 1. **ModelMyDiary.java**
   Represents a diary entry, storing details like title, description, date, image, and ID.

### 2. **DBManager.java**
   Handles database operations such as inserting, updating, deleting, and fetching diary entries from the SQLite database.

### 3. **Settings.java**
   Allows users to set and save their username using `SharedPreferences`.

### 4. **ViewDiaries.java**
   Displays a list of all diary entries and allows users to click on an entry to edit it.

### 5. **EditEntry.java**
   Allows users to edit an existing diary entry, modifying the title, description, or image.

---

## Screenshots

(Insert screenshots of the app interface here if available)

---

## How to Run the App

1. **Clone or Download the Repository:**
   Clone the repo or download it as a ZIP file.
   ```bash
   git clone https://github.com/chamodi0206/mydiary.git
