### README File


# 🌿 Yoga Pose Detection Web Application

Welcome to the **Yoga Pose Detection Web Application**, a cutting-edge platform designed to elevate your yoga practice through **real-time pose detection**, **session management**, **meditation support**, and **progress tracking**. Leveraging **computer vision** and **web technologies**, this tool offers an engaging experience for yoga enthusiasts, complete with a rich pose library, calming meditation audio, and tools for diet and progress tracking.

---

## ✨ Features

- **Real-Time Pose Detection** 🎯  
  Detects five yoga poses (*Tree Pose*, *Warrior 1*, *Warrior 2*, *Triangle Pose*, *Lord of Dance Pose*) using MediaPipe and OpenCV, with instant accuracy feedback and guided sequences.

- **Session Management** 📋  
  Create custom multi-pose sessions, track progress, and earn medals (*Bronze*, *Silver*, *Gold*, *Diamond*) based on accuracy (70%, 80%, 85%, 92%).

- **Yoga Information** 📚  
  A comprehensive library of 13 poses, including reference images and descriptions for poses like *Trikonasana*, *Bhujangasana*, and *Shavasana*.

- **Meditation Support** 🌊  
  Relax with five nature-inspired audio tracks (*Gentle Rain*, *Forest Ambiance*, *Ocean Waves*, *Soft Breeze*, *Flowing Stream*) via a simple audio player.

- **Progress Tracking** 📊  
  View detailed session history (timestamps, poses, accuracies, medals) and aggregated stats through a visual dashboard.

- **Diet Tracking** 🍎  
  Static meal planner templates with nutritional guidelines tailored for yoga practitioners.

---

## 🛠️ Tech Stack

### Backend
- **Python 3.8+** 🐍: Core programming language
- **Flask** 🌐: Web framework for API and routing
- **OpenCV (cv2)** 📹: Video processing and visualization
- **MediaPipe** 🕹️: Pose landmark detection
- **NumPy** 📈: Numerical computations
- **Flask-CORS** 🔗: Cross-origin resource sharing

### Frontend
- **HTML5** 📄: Page structure
- **CSS3** 🎨: Responsive styling
- **JavaScript** ⚡️: Client-side interactivity
- **Jinja2** 🖼️: Template rendering for Flask

### Dependencies
- `flask`
- `flask-cors`
- `opencv-python`
- `mediapipe`
- `numpy`

---

## 🚀 Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/nash-ds/YogaPose-Project.git
   cd YogaPose-Project/Backend
   ```

2. **Set Up Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application**:
   ```bash
   python app.py
   ```

5. **Back to Frontend foldre**:
   ```bash
   cd ~YogaPose-Project/Frontend
   ```

4. **Run the Application**:
   ```bash
   npm run dev
   open port localhost:8000 on your browser to access the application
   ```
   
---

## 📖 Usage

- **Home Page** 🏠: Explore yoga info at `/`.
- **Practice Yoga** 🧘: Try poses at `/yoga_try?pose=<pose_name>` (e.g., `Tree Pose`).
- **Start Session** 📅: Create multi-pose sessions at `/session`.
- **Meditate** 🌳: Play calming audio at `/meditation`.
- **Track Progress** 📈: View session results at `/session_results`.
  


---

## 🧪 Requirements

- Webcam for pose detection
- Modern browser (Chrome, Firefox, Edge)
- Stable internet for development server
- Python 3.8+ with required packages
