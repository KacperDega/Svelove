# Svelove: Polish Dating Application

<p align="center">
  <img src="docs/svelove-logo.svg" alt="Svelove Logo" width="400"/>
</p>

Svelove is a modern, full-stack dating application designed to help people in Poland find meaningful connections. At its core, Svelove is more than just a matching app; it's a platform for discovering new people who share your passions and are located nearby. By leveraging a rich database of Polish cities and a wide array of hobbies, it offers a tailored experience that goes beyond superficial swipes. Users can create detailed profiles, chat in real-time with their matches, and explore a community of individuals looking for genuine relationships. The application is built with a robust backend using Spring Boot and a dynamic frontend using React, ensuring a smooth user experience.

## ⚡️ Quick Stack
<div align="left">
  <img src="https://skillicons.dev/icons?i=java" height="40" alt="java logo"  />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=spring" height="40" alt="spring logo"  />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=idea" height="40" alt="intellijidea logo"  />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=postgres" height="40" alt="postgresql logo"  />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=supabase" height="40" alt="supabase logo"  />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=react" height="40" alt="react logo"  />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=ts" height="40" alt="typescript logo"  />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=tailwind" height="40" alt="tailwindcss logo"  />
  <img width="12" />
  <img src="https://img.daisyui.com/images/daisyui/mark-compressed.svg" height="40" alt="daisyui logo" />
  <img width="12" />
</div>

## ✨ Features
*   **User Profiles:** Create, edit, and view detailed user profiles with information such as photos, bio, hobbies, and preferences.
*   **Matching Algorithm:** A sophisticated algorithm that suggests potential partners based on factors such as user preferences, hobbies, and location.
*   **Messaging/Chat:** Real-time chat functionality to communicate with matches.
*   **Location-Based Filtering:** Find users in specific Polish cities and regions.
*   **Personalized Hobby Selection:** Choose from a list of hobbies popular in Poland to personalize your profile.
*   **Personal Statistics:** Track your activity with personal stats like swipes and matches, viewable for different time periods.

## 🖼️ Showcase

A gallery of screenshots from the application is available at the following link, showcasing the user interface and key features.

**[➡️ View Application Showcase](https://kacperdega.github.io/Svelove/)**

## 🛠️ Tech Stack

### Backend (Spring Boot)
*   **Spring Boot:** Core framework for building the application.
*   **Spring Security:** For authentication and authorization.
*   **Spring Data JPA:** For data persistence and interaction with the database.
*   **PostgreSQL:** Primary database for storing user data, profiles, and other information.
*   **Supabase Storage:** Secondary database for storing user photos.
*   **Springdoc OpenAPI:** For generating API documentation (Swagger UI).
*   **Polish City/Hobby Database:** Utilizes CSV datasets of Polish cities and hobbies for location-based filtering and personalized user profiles.

### Frontend (React)
*   **React:** For building the user interface.
*   **TypeScript:** For type-safe code.
*   **React Router:** For client-side routing and navigation.
*   **Tailwind CSS:** A utility-first CSS framework for styling.
*   **DaisyUI:** A component library for Tailwind CSS.
*   **StompJS & SockJS:** For real-time messaging and chat functionality via WebSockets.
*   **Polish-language Interface:** The user interface is designed in Polish to cater to the local market.

## 🔗 Repository Structure
*   **[Backend Repository](https://github.com/KacperDega/svelove-backend)** (The core API, business logic, and data layer.)
*   **[Frontend Repository](https://github.com/KacperDega/svelove-frontend)** (The user interface built with React.)
*   **[API Documentation (Swagger)](https://kacperdega.github.io/svelove-backend/)** (Detailed API endpoints reference.)

## 🚀 Getting Started

To run this project locally:

1.  **Clone the repository with its submodules:**
    ```bash
    git clone --recurse-submodules https://github.com/KacperDega/svelove.git
    ```

2.  **Set up and run the applications:**
    The backend and frontend are located in their respective submodules. Please refer to the `README.md` file within each submodule for detailed setup and run instructions.

