
# Language Exchange App

## Connecting Language Learners with Native Speakers

**This application is designed to create a vibrant community where language learners can connect with native speakers for authentic practice and cultural exchange. Our goal is to facilitate effective language acquisition through real-time interaction, fostering confidence and fluency in a supportive environment.**

## Table of Contents

* Project Overview
* Features
* Technologies Used
* Getting Started
  * Prerequisites
  * Frontend Setup (React)
  * Backend Setup (Java Spring Boot)
* Usage
* Contributing
* License

## Project Overview

**The Language Exchange App aims to bridge the gap between aspiring language learners and native speakers. By providing a platform for direct communication, users can engage in conversations, ask questions, and gain practical experience beyond traditional classroom settings. The application will support various languages and offer tools to enhance the learning experience.**

## Features

**Initial Features (as implemented or planned):**

* **User Interface:** A basic React frontend with a clean, responsive design.
* **User Authentication Placeholders:** Frontend includes buttons for Login and Register, which will connect to the Spring Boot backend.
* **Client-Side User ID:** A temporary user ID is generated on the client side, to be replaced by actual user IDs from the backend.

**Planned Features:**

* **Comprehensive User Authentication:** Secure sign-up, login, and session management handled by the Spring Boot backend.
* **Detailed User Profiles:** Users can specify native and target languages, interests, and availability.
* **Search & Matching:** Ability to find and connect with partners based on language criteria and other preferences via backend APIs.
* **Direct Messaging/Chat:** Real-time text and potentially voice chat functionality, fully managed by the Spring Boot backend (e.g., using WebSockets).
* **User Reputation/Feedback:** System for users to rate interactions.
* **Session Scheduling:** Tools to arrange and manage language exchange sessions.

## Technologies Used

### Frontend

* **ReactJS:** A JavaScript library for building user interfaces.
* **Tailwind CSS:** A utility-first CSS framework for rapid UI development and responsive design.
* **JavaScript fetch API (or Axios):** For making API calls to the Spring Boot backend.

### Backend

* **Java Spring Boot:** A powerful framework for building robust, stand-alone, production-grade Spring applications.
* **Spring Data JPA / Hibernate:** For efficient database interaction.
* **Spring Security:** For comprehensive authentication and authorization.
* **WebSockets (e.g., Spring WebSockets):** For real-time communication (e.g., chat, online status).

### Database (for Backend)

* **Relational Database (e.g., PostgreSQL, MySQL, H2):** To be used by the Spring Boot backend for persistent user data, chat history, user profiles, and other core application data.

## Getting Started

**Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.**

### Prerequisites

Before you begin, ensure you have the following installed:

* Node.js & npm/yarn: For the React frontend.
* Java Development Kit (JDK) 17 or newer: For the Spring Boot backend.
* Maven or Gradle: Build automation tools for the Spring Boot backend.
* A text editor or IDE: (e.g., VS Code, IntelliJ IDEA).
* Git: For version control.

### Frontend Setup (React)

1. Clone the repository:

   ```bash
   git clone https://github.com/davewish/languageexchangeapp.git
   cd language-exchange-app-frontend
   ```
2. Install dependencies:

   ```bash
   npm install
   # or
   yarn install
   ```
3. Configure Tailwind CSS:
   Ensure** **`tailwind.config.js` and** **`postcss.config.js` are correctly set up. The provided** **`App.jsx` already uses Tailwind classes.
4. Run the frontend:

   ```bash
   npm start
   # or
   yarn start
   ```

   The React app will typically run on** **[http://localhost:3000](http://localhost:3000/).

### Backend Setup (Java Spring Boot)

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd language-exchange-app/backend
   ```
2. Configure Database:

   * Set up your preferred relational database (e.g., PostgreSQL, MySQL).
   * Update** **`src/main/resources/application.properties` (or** **`application.yml`) with your database connection details.
   * Define your JPA entities and repositories.
3. Build the project:

   ```bash
   # Using Maven
   mvn clean install

   # Using Gradle
   ./gradlew build
   ```
4. Run the backend:

   ```bash
   # Using Maven
   mvn spring-boot:run

   # Using Gradle
   ./gradlew bootRun
   ```

   The Spring Boot application will typically run on** **[http://localhost:8080](http://localhost:8080/).

## Usage

Once both the frontend and backend are running:

1. Open your web browser and navigate to the frontend URL (e.g.,** **[http://localhost:3000](http://localhost:3000/)).
2. The application will display a temporary client-side user ID.
3. Use the "Login (Placeholder)" and "Register (Placeholder)" buttons.
4. Once authentication is implemented, the frontend will display the authenticated user's ID and allow for logout.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See** **`LICENSE` for more information.
