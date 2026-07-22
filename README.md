# 🍳 SwiftBites - Your Smart Cooking Companion

## ✨ Project Overview

SwiftBites is a modern Android recipe application designed to make meal planning and cooking easier, more enjoyable, and personalized. Built with **Kotlin** using modern Android development practices, it provides an intuitive user experience for discovering recipes, searching by ingredients, receiving meal reminders, and exploring nutritional information.

---

## 📚 Table of Contents

- [✨ Project Overview](#-project-overview)
- [🌟 Features](#-features)
  - [User Authentication](#user-authentication)
  - [Personalized Notifications](#personalized-notifications)
  - [Dynamic Home Menu](#dynamic-home-menu)
  - [Powerful Recipe Search](#powerful-recipe-search)
  - [Detailed Recipe View](#detailed-recipe-view)
  - [Smart Explore Menu (Ingredient-Based Recommendations)](#smart-explore-menu-ingredient-based-recommendations)
  - [Scalable Settings Menu](#scalable-settings-menu)
- [💻 Technologies Used](#-technologies-used)
- [🚀 Development Steps](#-development-steps)
- [💡 Scope for Improvement](#-scope-for-improvement-and-future-enhancements)
- [🛠️ How to Run Locally](#️-how-to-run-locally)
- [🎥 Video Demo](#-video-demo)

---

# 🌟 Features

SwiftBites provides a rich set of features to enhance your cooking experience.

## User Authentication

- **Secure Sign-Up**
  - Register using an email and password.
  - Password confirmation and validation.
  - Helpful error messages for invalid or existing accounts.

- **Secure Sign-In**
  - Fast login using saved credentials.

- **Credential Storage**
  - Login credentials are securely stored so users don't need to sign in every time.

---

## Personalized Notifications

- Receive **three daily meal suggestion notifications** (Breakfast, Lunch, Dinner).
- For demonstration purposes, notifications are configured to appear immediately after launching the app.

---

## Dynamic Home Menu

- Displays **10 randomly selected recipes**.
- Each recipe card includes:
  - Recipe name
  - Number of servings
  - Preparation time

---

## Powerful Recipe Search

- **Text Search**
  - Search by recipe name or ingredient.
  - Returns the 10 most relevant matches.

- **Voice Search**
  - Search hands-free using speech recognition.

---

## Detailed Recipe View

Selecting a recipe displays:

- High-quality images
- Recipe title
- Source URL
- Step-by-step cooking instructions
- Nutritional information
- Complete ingredient list

### Share Functionality

Users can easily share recipe links with friends and family.

---

## Smart Explore Menu (Ingredient-Based Recommendations)

- Search recipes using available ingredients.
- View recipes that best match your ingredients.
- Easily identify:
  - ✅ Ingredients you already have
  - ❌ Missing ingredients

### Input Validation

Ingredient names are validated to accept only alphabetical characters, reducing invalid searches.

---

## Scalable Settings Menu

- Toggle background music.
- Secure logout.
- Designed for future settings and customization options.

---

# 💻 Technologies Used

### Programming Language

- Kotlin

### Development Environment

- Android Studio

### UI

- Jetpack Compose
- Material Design 3

### Architecture

- MVVM Architecture

### Android Jetpack Libraries

- Core KTX
- AppCompat
- Activity
- ConstraintLayout
- Lifecycle Runtime KTX
- ViewPager2
- RecyclerView

### APIs & Cloud Services

- Spoonacular API
- Firebase Authentication
- Firebase Cloud Messaging (FCM)

### Networking

- Retrofit

### JSON Parsing

- Gson Converter

### Image Loading

- Picasso

### Testing

- JUnit
- AndroidX JUnit
- Espresso

### Version Control

- Git
- GitHub

---

# 🚀 Development Steps

1. Set up the Android Studio project.
2. Design the UI using Jetpack Compose and Material Design 3.
3. Create data models.
4. Integrate the Spoonacular API.
5. Implement Firebase Authentication.
6. Configure Firebase Cloud Messaging.
7. Develop recipe browsing, searching, and recommendation features.
8. Implement error handling and input validation.
9. Perform unit and UI testing.
10. Optimize performance and user experience.

---

# 💡 Scope for Improvement and Future Enhancements

Future versions of SwiftBites may include:

### Personalized Meal Planning

- Weekly meal schedules
- Calendar integration
- Goal-based meal recommendations

### Advanced Filtering

- Difficulty
- Cooking method
- Allergens
- Ratings
- Preparation time

### Community Features

- Upload recipes
- Recipe ratings
- Reviews
- Comments
- Follow favorite chefs

### Dietary Profiles

- Allergy preferences
- Health goals
- Personalized recommendations

### Offline Mode

- Download recipes for offline viewing.

### Interactive Cooking Mode

- Voice-controlled cooking
- Built-in timers
- Step-by-step cooking assistance

### Ingredient Substitutions

- Suggest suitable ingredient alternatives.

---

# 🛠️ How to Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git
cd YOUR_REPOSITORY_NAME
```

> Replace `YOUR_USERNAME` and `YOUR_REPOSITORY_NAME` with your actual GitHub username and repository name.

---

### 2. Open in Android Studio

1. Launch **Android Studio**.
2. Select **Open an Existing Android Studio Project**.
3. Navigate to the cloned project directory.
4. Open the project.

---

### 3. Sync Gradle

Android Studio should automatically sync the project.

If it doesn't:

- Click **Sync Project with Gradle Files** from the toolbar.

---

### 4. Build and Run

1. Connect an Android device **or** start an Android Virtual Device (AVD).
2. Click the **▶ Run** button.
3. Select your device.
4. The app will build, install, and launch.

---

# 🎥 Video Demo

Watch the demo here:

**https://drive.google.com/file/d/1ihYMHIAhBlLDHwcqQUlV5rFqtRwHyshR/view?usp=drive_link**
