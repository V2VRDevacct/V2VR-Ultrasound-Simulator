# V2VR Ultrasound Training Simulator README 

**Meta Quest 3 + Logitech MX Ink**  
Transforming the Meta Quest 3 and MX Ink into a precision VR ultrasound simulator for immersive echocardiography training.
<p align="center">
  <img src="assets/V2VR Short Video.gif" width="400"/>
</p>

📦 **Download APK:** [adu_e_d_ink_v1.0.1.apk](https://github.com/V2VRDevacct/V2VR-Ultrasound-Simulator/raw/refs/heads/main/adu_e_d_ink_v1.0.1.apk?download=)  📄 **Project One-Pager:** [View PDF](assets/V2VR_ProjectOnePager.pdf) ▶️ **Demo Video:** https://www.youtube.com/watch?v=dllDnrNrHAY  

---

## 🚀 Overview
This project is a fully immersive VR ultrasound training simulator built on the Meta Quest 3.

By integrating the Logitech MX Ink stylus as a tracked probe, users can perform realistic echocardiography scans with real-time feedback—enabling intuitive understanding of 3D anatomy and ultrasound imaging.

---

## 🩺 Key Features
- Precision probe tracking using MX Ink  
- Immersive VR/MR environments  
- Real-time feedback and guidance system  
- Spatial learning tools (cut plane + explorable 3D heart anatomy)  
- Interactive ultrasound machine interface with guided tutorial  
- Portable standalone system (no PC required)  

---

## ⚙️ Setup Instructions
The following should be completed within the Quest 3's Settings Menu before launching APK.

### 1. Environment
- Go to: **Settings → Environment Setup**
- Create Room Boundary: Create a **2.5m × 2.5m** or larger boundary area (recommended)
- Set Floor Boundary: Position the controller to the floor and confirm

- Recommended Play Modes:
- *Sandbox Room: seated or standing* 
- *Echo Room: seated at desk/table*

### 2. MX Ink Configuration
- Go to: **Settings → Devices → Stylus**  
- Pair the MX Ink  
- **Enable** *Left-Hand Use*

### 3. Tracking Settings
- Go to: **Settings → Tracking**  
- **Disable** *Automatically switch between controller and hands*

---

## ▶️ Launching the App
- Open **Library → Unknown Sources**  
- Run: `adu_e_d_ink`  
- User enters the **Main Lobby**  

---

## 🧪 Recommended Demo Walkthrough

### 1️⃣ Sandbox Mode (Spatial Learning)
- Select **Sandbox** in the Main Lobby 
- Note: controller UI can be toggled with **Y button**  
- Use both controllers to grab, stretch, and scale the heart  
- Walk inside or pull the heart towards you to explore its internal anatomy

**Cut Plane function:**
- On the controller UI, **Reset** the heart  
- Select **Cut Plane**
- Grab the cut plane and view 2D cross-sections  

- When finished, return to **Main Lobby**  

---

### 2️⃣ Echo Mode (Core Experience)
Select **Sandbox** in the Main Lobby

#### Calibration
- Align calibration points with table/desk edge → select **Next**  
- If no mannequin is available → select **Next**  
- Skip Machine Guide → proceed to Scan Room  

---

### 3️⃣ Scan Room Setup
- Hold MX Ink in **left hand** (probe)  
- Use **right controller** for UI Menu and machine interactions  

Toggle ON in Settings:
- Heart Mode (toggles between the transparent Heart and Patient view) 
- Cut Plane Mode  

💡 Demonstrates how 2D ultrasound images are generated from 3D anatomy (key learning moment)

---

### 4️⃣ Guided Scanning
- Select **Echo Guide** in the UI Menu 
- Select *Parasternal Long Axis*
- Watch instructional video to get overview of the probe placement 
- Select **Option A** or **Option B** guidance modes based on learning preference.
- When ready, position probe on the patient and follow visual guidance indicators.
- Adjust probe to acquire correct image
- *(Note: For image to appear on screen, probe must be touching the body surface)* 

⚠️ Without a mannequin, users will be “air scanning”  

---

### 5️⃣ Skills Testing
- Select **Take Test**  
- Perform scan without guidance  
- This test measures speed and accuracy  
- Press **Capture** on the machine when satisfied with image.
- This will exit test mode.  View results or Reset to retry.

---

### 6️⃣ Machine Training
- Open **Machine Guide**  
- Select **Interactive Tutorial** for guided step by step learning 

---

If users wish to explore further, they are welcome to visit the Library Room in the Main Lobby

---

## 🎥 Demo Video
👉 https://www.youtube.com/watch?v=dllDnrNrHAY

---

## 🧰 Hardware Requirements
- Meta Quest 3 (OS v2.1 or later)  
- Touch controllers  
- Logitech MX Ink stylus  
- Optional: mannequin, stand, and probe attachments (included in commercial version)  

---

## 🧠 Use Cases
Designed for:
- Medical students  
- Sonography training programs  
- Clinical education  
- Remote and scalable learning environments  

---

## 🔮 Future Development
- Clinical validation studies  
- Expanded modules (POCUS, pediatric, vascular)  
- Pathology libraries  
- Instructor dashboard (web-based SaaS platform)  

---

## 🤝 Acknowledgements
Built using:
- Unity  
- Meta Quest SDK  
- Logitech MX Ink  
