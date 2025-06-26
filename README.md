# Solo vs Multi Shooter Game

This project is a 2D shooting game developed in **Java** using **Swing** for the graphical user interface. It offers both single-player and real-time multiplayer experiences, built upon a clean and modular architecture. The game combines gameplay logic, responsive UI, audio-visual effects, and real-time communication between players.

---

## Game Architecture

The application is organized around several key components:

- **`JeuInterface.java`**: Main class managing the game flow and interface
- **`AudioManager.java`**: Handles background music and sound effects
- **`ScoreDatabase.java`**: Persists player scores in a local database
- **Client-server system**: Enables **real-time multiplayer chat**

---

## Main Features

-  **Level progression**: Difficulty increases through tiers (Beginner → Master)
-  **Four unique aircrafts**:  
  - *MiG-51S*  
  - *F/A-28A*  
  - *Su-55*  
  - *Su-51K*  
  Each has its own stats and abilities.
-  **Life system** with temporary invincibility after collisions
-  **Dynamic scoring**: Bonuses awarded for precision and successful hits
-  **Integrated chat**: Real-time player communication in multiplayer mode
-  **Smooth animations**: Visual polish for shots, collisions, and effects

---

##  Technical Highlights

-  **Multithreading**: Used to handle movement and collision detection
-  **Optimized collisions**: Based on fine-tuned collision rectangles
-  **Efficient resource handling**: Images and sounds are managed for performance
-  **Client-server architecture**: Ensures low-latency chat and interaction
-  **Responsive UI**: Swing components enhanced with animation for fluid experience

---

##  Multimedia Resources

-  **Custom sprites** for jets, projectiles, and explosion effects
-  **Sound effects**: Shooting, explosions, and level transitions
-  **Modern UI**: Smooth screen transitions and animations

---

##  Security &  Performance

-  Secure and stable **network communication** via Radmin VPN
-  Performance optimized through:
  - Use of `CopyOnWriteArrayList` for projectile management
  - Thread separation for heavy computations
-  Proper **cleanup** of all resources on game exit

---

##  Technologies Used

- **Java** (core programming language)
- **Swing** (GUI framework)
- **SQL** (score persistence via `ScoreDatabase`)
- **Radmin VPN** (for establishing virtual multiplayer network)

---

##  Network Configuration

To enable multiplayer and real-time chat:
- **Radmin VPN** is used to create a secure virtual LAN between players
- This ensures:
  - Stable and secure peer-to-peer connection
  - Low latency for fluid multiplayer interactions
  - Simple and user-friendly network setup
  - Possibility to play remotely with friends

---

##  Authors

This game was developed by:

- **ESSEBAIY Aya**
- **TAFRAOUTI Sanae**   
- **ELMESSAOUDI Fatima**

---

Enjoy battling it out in the skies—whether solo or with friends! 🚀
