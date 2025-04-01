# Theia - Intelligent Photo Sharing & Management App

Theia is an AI-powered photo sharing and management application designed to offer an intuitive and intelligent experience for capturing, organizing, and sharing your memories.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Setup & Installation](#setup--installation)
- [Usage](#usage)
- [License](#license)

---

## Overview

Theia harnesses the power of artificial intelligence to simplify and enhance your photo sharing experience. It not only allows you to capture great photos with advanced camera controls but also organizes and edits your photos automatically using state-of-the-art AI techniques.

---

## Features

- **Advanced Camera Controls**  
  Customize settings like ISO, focus, and grid overlays for the perfect shot.
  
- **Automated Image Organization**  
  Smart sorting by date, location, and even face recognition to keep your gallery organized.
  
- **Facial Recognition & Clustering with ML**  
  Powered by DeepFace (FaceNet, VGG-Face), Theia groups similar faces together for easy retrieval.
  
- **Real-Time Sharing & Collaboration**  
  Seamless integration with Supabase and Firebase enables real-time sharing and collaboration.
  
- **Robust Search Capabilities**  
  Efficient metadata, face, and keyword search to help you quickly find your photos.
  
- **Built-in Editing Tools**  
  Enjoy editing features such as filters, captions, and freehand drawing.
  
- **Seamless Video Recording & Editing**  
  Integrated video functionalities to capture and edit videos on the go.

---

## Tech Stack

### Front-End
- **Flutter**  
  Cross-platform mobile development framework for creating beautiful native apps.

### Back-End
- **FastAPI (Python)**  
  High-performance API framework.
- **RabbitMQ & Celery**  
  For background processing and task management.

### Database & Cloud
- **Supabase**  
  Storage and real-time synchronization.
- **Firebase**  
  Authentication and notifications.

### AI & Image Processing
- **DeepFace**  
  Utilized for robust facial recognition and clustering capabilities.

---

## Setup & Installation

### Clone the Repository

```bash
git clone https://github.com/CREVIOS/Thiea
cd Thiea_app
```
## Run the Mobile App

Ensure you have Flutter installed. Then, execute the following commands:

```bash
flutter pub get
flutter run
```

## Run the Backend

* Ensure Python 3.9+ is installed.

* Navigate to the backend folder.

* Follow the instructions in the backend's README file to set up the environment and run the server.


## License

Theia is released under the MIT License.

Enjoy using Theia and transforming the way you capture and share memories!
