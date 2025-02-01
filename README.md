# VR-Compatible Roller Coaster Ride

## Project Overview
This project creates an immersive VR experience featuring a university campus, a shooting game, and a roller coaster ride. Developed using **Unity** and optimized for **Meta Quest 2**, it combines exploration, interaction, and physics-based motion for a realistic VR environment.

## Features
- **Campus Exploration** – Free-roam VR movement.
- **Roller Coaster Ride** – Realistic physics-based simulation.
- **Shooting Game** – Interactive gameplay with virtual targets.
- **VR Optimization** – Head tracking, motion smoothing, and spatial audio.

## Running the Project

### Prerequisites
- **Unity (Version used: [Specify version])**
- **Meta Quest 2**
- **XR Plugin & Meta Quest 2 SDK**

### Steps to Run
1. **Clone the Repository**
   ```sh
   git clone https://github.com/mrrutvikvasoya/Roller_Coaster_VR_Game.git
   cd [project_folder]
   ```  
2. **Open in Unity**
   - Launch Unity and open the project folder.
   - **Note:** The **Library** folder is not included here due to large file size. Unity will regenerate it.

3. **Import Dependencies**
   - Ensure all required Unity packages (XR Plugin, Meta Quest SDK) are installed.
   - If missing, install them via **Unity Package Manager**.

4. **Build and Run**
   - Connect **Meta Quest 2** to your PC.
   - Switch to **Android Platform** in Unity Build Settings.
   - Click **Build & Run** to deploy the app.

### First-Time Running
- The first run may take **extra time** as Unity compiles and optimizes assets.
- Subsequent runs will be **faster** due to cached resources.

## Known Issues (Bugs)
- **Sound Issues:** Audio distortion in high-speed sections.
- **Object Pickup:** Difficulty grabbing objects.
- **Movement Restrictions:** Players stuck while holding objects.
- **Boundary Glitches:** Players falling through edges in some cases.

## Future Improvements
- Bug fixes and performance optimizations.
- Multiplayer mode integration.
- Additional mini-games and expanded environments.
