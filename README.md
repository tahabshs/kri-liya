# Kri Liya

**A peer-to-peer platform for renting and lending everyday objects.**

Kri Liya is a collaborative student project that aims to make renting and lending objects easier. Instead of buying items that are only needed occasionally, users can discover objects offered by other people and request to rent them for a specific period.

The project is developed as part of a four-week team project using Scrum, Jira, and GitHub.

## 🎯 Project Objectives

- Allow users to publish and manage object listings.
- Help users discover available objects through search and filters.
- Enable users to submit and manage rental requests.
- Prevent overlapping confirmed rentals for the same object.
- Provide a simple, clear, and user-friendly experience.
- Practice teamwork, Agile project management, and collaborative development.

## ✨ Main Features (MVP)

- **Authentication:** User registration, login, and logout.
- **Object Listings:** Create, view, update, and delete your own listings.
- **Search & Filters:** Browse objects and filter by category, location, and price.
- **Rental Requests:** Request to rent an object for specific dates.
- **Request Management:** Owners can accept or refuse rental requests.
- **Availability Management:** Prevent conflicting confirmed rentals.
- **User Dashboard:** Manage your listings and rental requests.

## 🛠️ Technologies

| Technology | Purpose |
|---|---|
| React | Frontend user interface |
| Laravel (PHP) | Backend and application logic |
| MongoDB | Database |
| Git & GitHub | Version control and collaboration |
| Jira | Task management and Scrum planning |

## 👥 Team & Methodology

Kri Liya is developed by a team of six students using the Scrum methodology.

- **Project duration:** 4 weeks
- **Project management:** Jira
- **Source code management:** GitHub
- **Workflow:** Backlog, sprint planning, development, testing, and review

The work is organized into four one-week sprints, with regular integration and testing throughout development.

## 🚀 Getting Started

Installation instructions will be added once the frontend, backend, and database configuration are finalized.

### Prerequisites

- Node.js and npm
- PHP and Composer
- Laravel-compatible MongoDB integration
- MongoDB instance

### Installation

Setup instructions for the frontend and backend will be documented here as the project develops.

## 📌 Project Scope

### Included in the MVP
- Authentication and user profiles
- Object listing management
- Search and filtering
- Rental requests and availability validation
- Basic user dashboard

### Not Included in the MVP
- Online payments
- Live chat
- Real-time notifications
- Reviews and ratings
- Mobile application
- Advanced identity verification

## 🔐 Security & Validation

The application should ensure that:
- Only authenticated users can request rentals.
- Users can modify or delete only their own listings.
- Rental dates are valid.
- Confirmed rentals do not overlap for the same object.
- Sensitive information and environment variables are not committed to GitHub.

## 📂 Project Structure

The repository is planned to follow this structure:

```text
kri-liya/
├── frontend/       # React application
├── backend/        # Laravel application
├── docs/           # Project documentation
└── README.md       # Project overview
```

The structure may evolve during development.

## 🤝 Contribution Guidelines

1. Clone the repository.
2. Create a feature branch from the agreed development branch.
3. Implement your assigned Jira task.
4. Test your changes.
5. Open a Pull Request and link it to the relevant Jira issue.
6. Request a review before merging.

**Branch naming examples:**
- `feature/KL-01-authentication`
- `feature/KL-02-object-listings`
- `fix/KL-03-rental-validation`

Do not commit `.env` files, passwords, API keys, or other secrets.

## 📅 Development Roadmap

- **Sprint 1:** Project setup, database integration, and authentication.
- **Sprint 2:** Object listings and listing management.
- **Sprint 3:** Search, filters, and rental requests.
- **Sprint 4:** Dashboard, integration, testing, documentation, and final demonstration.

## 📄 Project Status

**Status:** In development.

This project is an educational MVP. Features, documentation, and setup instructions will be updated as development progresses.

---

*Built collaboratively by the Kri Liya team.*