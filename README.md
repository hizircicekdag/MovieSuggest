# Movie Suggest Android Mobile App

## Project Description
Movie Suggest is an **Android mobile application** that utilizes the **TMDB API** to provide movie recommendations to users. Users can add their favorite movies, view detailed information about them, and receive personalized movie suggestions using advanced filters. The app also uses **Firebase** for authentication and database management.

## Technologies Used
- **Android Studio** (Development Environment)
- **Java** (Main programming language)
- **Firebase**
    - **Realtime Database**
    - **Firestore Database**
    - **Authentication**
- **TMDB API** (For retrieving movie data)

## Features
### **1. User Authentication**
- Users can log in or register a new account.
- Secure authentication is provided via Firebase Authentication.

### **2. Main Page**
- **Movie Search:** Users can search for movies by name.
- **Best Movies:** Lists movies with an IMDb rating of 7.5 or higher.
- **Category-Based Movies:** Movies are categorized for easy browsing.
- **Popular Movies:** Displays the most popular movies among users.
- **Movie Details Access:** Clicking on a movie poster navigates to the detailed movie page.

### **3. Movie Detail Page**
- Displays movie title, IMDb rating, duration, summary, and actors.
- **Add to Favorites:** Users can add or remove movies from their favorites.

### **4. Favorites Page**
- Displays a list of favorited movies.
- Users can navigate to detailed movie pages.

### **5. Suggest Page**
- Users can receive movie recommendations based on selected filters.
- Available filters:
    - **Category**
    - **Publication Year**
    - **Film Language**
    - **Search for Actors**
    - **Duration**
    - **IMDb Rating**
    - **Adult Content Filtering**

### **6. Profile Page**
- Users can log out.
- Name and password can be updated.

## Installation Steps
### **⚠ Important Notice**
Before using the application, ensure that you have completed the necessary **API setup**:
- **Firebase:** Set up Firebase Authentication and Firestore Database.
- **TMDB API:** Obtain an API key from TMDB and configure it in your project.

### **Setup Guide**
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/hizircicekdag/MovieSuggest.git
   ```
2. **Open in Android Studio** and import the project.
3. **Configure Firebase:**
    - Create a new Firebase project in the Firebase Console.
    - Set up Firestore Database and Authentication.
    - Add the `google-services.json` file to the `app/` directory.
4. **Configure TMDB API:**
    - Create an account on TMDB and obtain an API key.
    - Store the API key in `gradle.properties` or a configuration file.
5. **Install dependencies and run the project.**

## Contributing
If you would like to contribute to this project, follow these steps:
1. Fork this repository.
2. Create your own branch: `git checkout -b new-feature`.
3. Make your changes and commit them: `git commit -m 'Added new feature'`.
4. Push your branch: `git push origin new-feature`.
5. Open a pull request.

## License
This project is **open source** and can be used without any licensing restrictions.

---
If you have any questions or feedback, feel free to get in touch! 🎬🍿

