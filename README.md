# Library Management Mobile App

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

A full-stack mobile app for library management with Librarian (manage books/users) and Reader (borrow books) roles. Built with Java Spring Boot (MongoDB) and Flutter, deployed on Heroku, and managed in a single GitHub repo.

## Features
- **Roles**: Librarian (add/remove books, reports), Reader (borrow/return, history with fines).  
- **UI**: Modern Flutter frontend with book images.  
- **Backend**: REST API with JWT, deployed on Heroku.  
- **Extras**: Search, image upload, role management.

## Tech Stack
- **Backend**: Java (Spring Boot), MongoDB  
- **Frontend**: Flutter (Dart)  
- **Tools**: Git, GitHub, Heroku  


## Prerequisites
- Java JDK 17+  
- Flutter SDK  
- MongoDB (local/Atlas)  
- Git  
- Heroku CLI  

## Setup
### Backend
1. Go to `backend/`.  
2. Install dependencies (e.g., via Maven).  
3. Configure MongoDB in `application.properties`.  
4. Set env vars: `MONGODB_URI`, `JWT_SECRET`.  
5. Run locally and test.

### Frontend
1. Go to `frontend/`.  
2. Add `http`, `cached_network_image` to `pubspec.yaml`.  
3. Run `flutter pub get`.  
4. Set API URL to deployed backend.  
5. Run `flutter run` on emulator/device.

## Deployment
- **Backend**: In `backend/`, use Heroku CLI, set env vars, deploy with `git subtree push --prefix backend heroku main`.  
- **Frontend**: Build APK with `flutter build apk`, connect to deployed backend.

## Usage
- Librarian: Add books, view reports.  
- Reader: Borrow books, check history/fines.

## Contributing
- Fork, branch, commit, push, and submit a pull request.

## License
MIT License - see [LICENSE](LICENSE).

## Contact
- GitHub: [your-username](https://github.com/your-username)  
- Email: your-email@example.com
