# esp32_facerec
a mini project for future career
## File structure 

esp32_facerec/
├── README.md
├── .env.example
├── requirements.txt
├── config/
│   └── settings.yaml
│
├── firmware/                    # ESP32-CAM code
│   ├── platformio.ini
│   ├── include/
│   │   └── config.example.h
│   └── src/
│       └── main.cpp
│
├── backend/                     # Python application
│   ├── __init__.py
│   ├── main.py                  # API/application entry point
│   ├── config.py
│   │
│   ├── api/
│   │   ├── camera_routes.py
│   │   └── face_routes.py
│   │
│   ├── recognition/
│   │   ├── detector.py
│   │   ├── encoder.py
│   │   └── matcher.py
│   │
│   ├── services/
│   │   ├── enrollment_service.py
│   │   ├── recognition_service.py
│   │   └── attendance_service.py
│   │
│   ├── database/
│   │   ├── models.py
│   │   └── repository.py
│   │
│   └── schemas/
│       └── face.py
│
├── data/
│   ├── faces/                   # Enrollment images
│   ├── encodings/               # Generated face embeddings
│   └── database/                # SQLite database
│
├── scripts/
│   ├── enroll_face.py
│   └── test_camera.py
│
└── tests/
    ├── test_detector.py
    └── test_matcher.py