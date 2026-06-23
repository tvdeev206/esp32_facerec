# esp32_facerec

Computer vision project (Arduino/ESP32) file structure:

```text
esp32_facerec/
├── README.md
├── platformio.ini
├── arduino/
│   ├── esp32_facerec.ino
│   ├── camera_pins.h
│   ├── config.h
│   ├── face_detect.h
│   ├── face_detect.cpp
│   ├── face_recognize.h
│   ├── face_recognize.cpp
│   ├── camera_stream.h
│   ├── camera_stream.cpp
│   ├── web_server.h
│   └── web_server.cpp
├── data/
│   ├── index.html
│   ├── app.js
│   └── style.css
├── include/
│   └── project_version.h
├── lib/
│   ├── cv_utils/
│   │   ├── cv_utils.h
│   │   └── cv_utils.cpp
│   └── camera_drivers/
│       ├── camera_drivers.h
│       └── camera_drivers.cpp
├── src/
│   └── main.cpp
└── test/
    └── test_main.cpp
```
