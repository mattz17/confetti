![confetti](https://github.com/mattz17/confetti/assets/47068683/6fc2ce62-4c4a-423d-be1b-1f93544a0714)

# Confetti Event Management System

## Overview

The **Confetti Event Management System** is a comprehensive Java-based application designed to streamline event management, messaging, raffles, room assignments, user interactions, and more. It adheres to the MVC architecture, clearly separating logic, management, and user interfaces.

---

## Project Structure

### Main Components

- **Event Management**: Manage the lifecycle of events (creation, validation, manipulation).
- **Messaging System**: User-to-user messaging functionalities.
- **Raffle System**: Conduct and manage event raffles.
- **Room Management**: Assign and handle rooms efficiently.
- **Request Handling**: Process and manage user-generated requests.
- **User Signup & Authentication**: Manage user registration and authentication.
- **System Controllers**: Provide role-based administrative and user interfaces.

### Directory Structure

- `event/`: Controllers, managers, presenters, entities for events.
- `messaging/`: Message-related controllers, presenters, and managers.
- `raffle/`: Raffle functionalities.
- `room/`: Room assignment and management.
- `requests/`: Handling and managing user requests.
- `signup/`: User registration and authentication.
- `startup/`: Initial system setup and utilities.
- `system/`: Controllers tailored for specific user roles.
- `user/`: User management including roles and interactions.
- `view/`: User interface and interaction prompts.
- `gateway/`: Persistence layer for data storage and retrieval.

---

## Key Functionalities

### Event Management
- Event lifecycle operations and persistent storage.

### Messaging System
- Send, view, manage, and delete messages efficiently.

### Room Allocation
- Manage event room assignments and availability checks.

### Raffle System
- Execute raffles and handle winner announcements.

### Request Management
- User requests handling for event participation and resources.

### User Management
- Role-based user management and interaction.
- Support for Admin, Organizer, Attendee, Speaker, and VIP roles.

### Authentication
- Comprehensive signup, login, and system initialization.

---

## Technologies Used

- **Java**
- **MVC Architecture**
- **Serialization**

---

## Installation

```bash
git clone [REPOSITORY_URL]
cd confetti-main
javac Main.java
java Main
```

---

## Usage

- Create or log into an account.
- Navigate menus based on your role.
- Manage events, messages, raffles, rooms, and more.

---

## Contributing

Contributions are welcome!

- Fork the repository
- Create a feature branch: `git checkout -b feature/your-feature`
- Commit changes: `git commit -am 'Your commit message'`
- Push to your branch: `git push origin feature/your-feature`
- Open a pull request
