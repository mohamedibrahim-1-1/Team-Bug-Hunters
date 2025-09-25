# Movito team

Welcome to **Movito team** repository!  
We are a group of passionate developers working together on Android projects using **Kotlin, Jetpack Compose, and modern development practices**.

---

## 👥 Team Members
- **Mohamed Ibrahim Abdel-Samee** (Team Leader)  
- **Youssef Sayed**  
- **Yehia Mohamed**  
- **Ahmed Essam**  
- **Basmala Wahid**  
- **Alyaa Osama**

---

## 🎬 Project Name
**Movito (Movie Discovery App)**

---

## 🎯 Project Idea
We are building a **Movie Discovery App** that allows users to:
- Browse **popular movies** in a beautiful grid layout.  
- View **detailed information** about a selected movie (title, synopsis, rating, release date).  
- **Search** for movies by title.  
- Enjoy a **modern UI/UX** powered by **Jetpack Compose** and **Material Design 3**.

---

## ⚡ Technologies
- **Language:** Kotlin  
- **UI Toolkit:** Jetpack Compose  
- **Networking:** Retrofit / OkHttp   
- **Image Loading:** Coil  
- **Architecture:** MVVM / Clean Architecture  
- **Database:** Room (for caching/offline mode)  
- **Version Control:** Git & GitHub  
- **Testing:** Unit Testing + Compose UI Testing  
- **Security:** Secure API key storage using `gradle.properties` (no hardcoded keys)  

---

## 🗓️ Project Plan

### Week 1 – Project Setup & Core UI
**Goals:**
- Set up project structure in **Android Studio**.
- Configure Gradle dependencies (**Jetpack Compose, Retrofit/OkHttp, Coroutines, Coil**, etc.).
- Define app architecture (**MVVM** or **Clean Architecture**).
- Create mock data to design UI without API.
- Build core screens with Compose:
  - **Home Screen** (list/grid of movies)
  - **Movie Details Screen** (basic layout)
- Navigation setup with **Navigation-Compose**.

✅ **Deliverable:** Functional app with navigation and mock UI for movie list & details.

---

### Week 2 – API Integration & Data Layer
**Goals:**
- Connect to the chosen API (**TMDB API**).
- Implement **Retrofit** for network calls.
- Set up data layer (**Repositories, DTOs, Models**).
- Use **Coroutines + Flow** for async data.
- Replace mock data with real API responses.
- Implement error handling & loading states.

✅ **Deliverable:** Movie list fetched from API and displayed in the Home Screen.

---

### Week 3 – Features & State Management
**Goals:**
- Implement **search functionality** (search movies by name).
- Add filtering/sorting (optional).
- Integrate **pagination** (infinite scroll).
- Improve UI with **Material3** design.
- Apply proper state handling (using **StateFlow** or **ViewModel**).
- Cache data with **Room** (optional, for offline mode).

✅ **Deliverable:** Searchable, filterable movie list with smooth scrolling and polished UI.

---

### Week 4 – Testing, Polish & Deployment
**Goals:**
- Unit tests for **ViewModel** & **Repository**.
- UI tests with **Compose Testing**.
- Optimize performance (lazy grids, image loading).
- Improve UX (skeleton loaders, error dialogs).
- Add **splash screen** & app icon.
- Prepare Play Store-ready build (if needed).

✅ **Deliverable:** Fully functional, tested, and polished Movie Discovery app.

---

## 🔧 Team Members' Tasks
1. **Mohamed Ibrahim & Youssef Sayed**  
   Responsible for UI and Jetpack Compose (Home screen, Detail screen, theming).

2. **Yehia Mohamed & Ahmed Essam**  
   Responsible for backend development, data layer, and API integration with Retrofit/Coroutines.

3. **Basmala Wahid & Alyaa Osama**  
   Responsible for testing, documentation, animations, and UI polish.
