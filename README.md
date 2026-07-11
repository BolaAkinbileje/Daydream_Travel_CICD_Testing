# DevOps Week 2 Lab

# Daydream Travel System CI/CD Testing

## Overview
The Daydream Travel System is a pre-existing Python and Flask web application that simulates a travel booking platform for educational and software testing purposes. As part of a DevOps laboratory exercise, the application was extended with a **Booking Search** feature that allows authenticated users to search their bookings by destination from the dashboard.

The repository was also used to practise key DevOps activities, including Git branching and merging, automated testing, and Continuous Integration (CI) using GitHub Actions.

## Purpose
This project is intended to:

- Demonstrate Git and DevOps workflows in a practical setting.
- Provide examples of extending an existing application with new functionality.
- Demonstrate automated testing and Continuous Integration practices.
- Serve as a practice environment for software testing methodologies.
- Illustrate how version control, automation and CI improve software quality and delivery confidence.

## Important Note
**This is not a production-ready application.** The system has been developed for educational purposes and may contain simplified functionality and intentionally limited implementations to support learning activities.

## Features
The application includes simplified versions of:

- Travel package browsing
- Booking management
- User authentication
- Amenity management
- Travel itinerary planning
- **Booking search by destination from the user dashboard** (extension implemented during the DevOps lab)

## DevOps Enhancements Completed
The following DevOps activities were completed as part of the lab:

- Created and worked from a dedicated feature branch (`feature/booking-search`).
- Implemented and merged a new feature using meaningful incremental commits.
- Added an automated integration test for the booking search functionality.
- Configured a GitHub Actions CI pipeline to:
  - Install dependencies
  - Execute unit tests
  - Execute integration tests
  - Provide rapid feedback on code changes.
- Demonstrated successful CI execution on both the feature branch and `main`.

## Technology Stack
- Python
- Flask
- Pytest
- Git and GitHub
- GitHub Actions

## Getting Started

### Prerequisites
- Python 3.9 or later
- pip package manager
- Git

### Installation
```bash
git clone https://github.com/BolaAkinbileje/Daydream_Travel_CICD_Testing.git
cd Daydream_Travel_CICD_Testing
pip install -r requirements.txt
```

### Run the Application
```bash
python app.py
```

The application will be available locally at:

```text
http://127.0.0.1:5000
```

## Running Tests
Run all unit and integration tests:

```bash
pytest tests/unit tests/integration
```

## Continuous Integration
The project uses **GitHub Actions** to automatically validate changes whenever code is pushed. The CI pipeline:

1. Checks out the repository.
2. Installs project dependencies.
3. Runs automated tests.
4. Reports success or failure, providing fast feedback to developers.

## Learning Outcomes Demonstrated
This repository demonstrates:

- Version control using Git.
- Feature branching and merging.
- Continuous Integration.
- Automated testing.
- Small batch development and incremental delivery.
- DevOps principles including automation, fast feedback and traceability.

## License
This project is provided for educational purposes only.

---
**Author:** Bola Akinbileje  
**Module:** DevOps - CSO7024  
**Repository:** Daydream_Travel_CICD_Testing
