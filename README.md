# Intellihand

Gesture Controlled Virtual Mouse + Voice Recognition


Enhance human-computer interaction with the Gesture Controlled Virtual Mouse, which utilizes hand gestures and voice commands to simplify tasks. This innovative project minimizes direct contact with the computer, enabling all I/O operations to be virtually controlled. Leveraging advanced machine learning and computer vision algorithms, it seamlessly recognizes both static and dynamic hand gestures, as well as voice commands, without the need for additional hardware. The system employs state-of-the-art models like CNN, implemented via MediaPipe and running on pybind11. It includes two modules: one that detects gestures directly from hands using MediaPipe Hand detection, and another that works with gloves of any uniform color. Currently, this project is designed for the Windows platform.


## Features

### Gesture Recognition:

* **Neutral Gesture**
* **Move Cursor**
* **Left Click**
* **Right Click**
* **Double Click**
* **Scrolling**
* **Drag and Drop**
* **Multiple Item Selection**
* **Volume Control**
* **Brightness Control**

### Voice Assistant (Proton):

* **Launch / Stop Gesture Recognition**
* **Google Search**
* **Find a Location on Google Maps**
* **File Navigation**
* **Current Date and Time**
* **Copy and Paste**
* **Sleep / Wake up Proton**
* **Exit**

This project showcases the integration of cutting-edge technology to create a hands-free, efficient, and user-friendly interaction system.


git clone https://github.com/ahanban15/Intellihand

```
pip install virtualenv
```

```
cd my-project
virtualenv --python C:\Path\To\Python\python.exe venv
```

```
.\venv\Scripts\activate
```

```
pip install -r requirements.txt
```

```
python Gesture_Controller.py
```
