# AutoSmart-Infotainment
**Project Overview**
FaceDrive-Infotainment is a cutting-edge car infotainment system that integrates facial recognition technology to offer a personalized, secure, and user-friendly experience. Designed with a sleek, intuitive UI/UX using Figma, this system activates upon recognizing a registered user, ensuring secure access to a vehicle's infotainment system. The project combines advanced Python programming with OpenCV for face detection, making it a step forward in modern automotive technology.

**Features**
Facial Recognition Authentication: The system authenticates users using OpenCV and a Haar Cascade classifier to detect and match faces from a pre-registered database.
Infotainment System:
  - Music Player: Control music playback.
  - Navigation: Real-time GPS and map integration.
  - Vehicle Settings: Access to settings like climate control, driving modes, etc.
  - Phone Integration: Bluetooth calling, messaging, and app mirroring.
  - Entertainment Options: YouTube, screen mirroring, and more.
  - Security: The system only unlocks when the authorized user's face matches the database.

**Technologies Used**
UI/UX: Figma for designing intuitive and seamless interfaces.
Programming Languages: Python for backend facial recognition integration.

**Libraries:**
OpenCV for face detection and recognition.
SQLite for storing user face data.
Haar Cascade for facial feature extraction.

**How It Works**
The system prompts the user to scan their face using a connected camera.
The face is compared against the pre-stored database using OpenCV.
If a match is found, the infotainment system unlocks, displaying the home screen with all available options.
Users can interact with various infotainment features, ranging from media control to vehicle settings.

**Future Enhancements**
Integration with voice recognition for hands-free control.
Expansion of media and vehicle options.
Cloud-based user data storage for multi-vehicle access.
