https://github.com/user-attachments/assets/9051611d-b941-44ac-a52d-52c0f5653499

Age of Chivalry 🏰⚔️
A medieval Roblox game featuring mounted c

https://github.com/user-attachments/assets/80c8fc4e-03bf-483a-9686-419a5764f622

ombat, jousting tournaments, and third-person action gameplay.
🎮 Project Overview
Age of Chivalry is an immersive medieval combat experience built in Roblox, combining realistic horse mechanics, jousting physics, and a custom third-person camera system for an authentic knight combat experience.

✨ Features Implemented
🐴 Horse Movement System

Realistic Horse Physics

Variable speed galloping with acceleration/deceleration
Stamina system that affects horse speed and performance
Smooth turning mechanics with speed-based turn rates
Dynamic camera shake during galloping for immersive feel


Stamina Mechanics

Real-time stamina drain during sprinting
Automatic regeneration when walking or idle
Visual feedback system for stamina levels
Speed penalties when stamina is depleted


Horse Mounting/Dismounting

Seamless mounting system with proximity detection
Smooth dismount with proper player positioning
Tool handling during mount/dismount transitions



🎯 Jousting System

Lance Combat Mechanics

Physics-based damage calculation using relative velocity
Speed-dependent damage system (faster = more damage)
Hit detection with proper collision handling
Visual and audio feedback on successful hits


Lance Breaking System

Dynamic lance fracture on impact
Three break types: Top, Middle, Bottom
Visual representation of broken lances
Network replication for multiplayer consistency
Automatic lance respawn after breaking


Combat Animations

Hold stance animation
Ready position for charging
Strike/smash animation on impact
Hit reaction animations


Mounted Combat

Lance wielding while riding horses
Speed-based damage multipliers
Realistic jousting physics
Tournament-ready mechanics



📷 Custom Third-Person Camera System

Advanced Camera Controls

Smooth mouse-look camera rotation
Variable zoom (0.5 - 15 studs)
First-person mode at close zoom
Third-person perspective at far zoom
Mouse lock with right-click protection


Body Part Rotation System

Dynamic neck rotation for head tracking
Waist articulation for upper body movement
Root rotation for full body turning
Different rotation limits for horse vs ground movement


Multiplayer Synchronization

Real-time body rotation replication
Network-efficient update system (10Hz)
Smooth interpolation for other players
Camera shake synchronization


Smart Transparency System

Character becomes transparent in first-person
Tool exclusion (weapons stay visible)
Smooth transition between view modes
Part caching for performance



🎨 Visual Polish

Camera Effects

Dynamic horse gallop camera shake
Intensity scales with horse speed
Smooth camera transitions
Occlusion handling


Lance Visual Feedback

Full lance model during normal use
Shattered/broken pieces on impact
Proper piece visibility management
Networked visual updates



🔧 Technical Systems
Client-Side Scripts

ThirdPersonCamera - Advanced camera controller in StarterPlayerScripts
LanceScript - Local lance handling and visual feedback
StaminaSystem - Client-side stamina UI and management
HorseMovement_Client - Client prediction and smooth movement

Server-Side Scripts

BodyRotation (RemoteEvent) - Syncs player body rotations across clients
BreakLance (RemoteEvent) - Handles lance break replication
Lance respawn system with automatic tool regeneration

Network Architecture

Efficient client-server communication
Event-based replication system
Optimized update rates (10Hz for body rotation)
Client-side prediction for responsive controls


🛠️ Technical Highlights
Performance Optimizations

Character part caching to reduce FindFirstChild calls
Frame-limited network updates for body rotation
Smart tool detection for transparency system
Efficient RenderStep binding for camera updates

Bug Fixes Completed

✅ Mouse lock no longer breaks on right-click
✅ Zoom properly transitions to first-person view
✅ Fixed lance break type variable mismatch
✅ Resolved stamina system performance issues
✅ Camera following mouse input properly
✅ Body rotation replication working correctly

Code Quality

Modular script architecture
Clear separation of client/server logic
Comprehensive error handling
Debug logging for development
Well-commented code sections


🎯 Key Gameplay Features

Mounted Combat - Players can engage in high-speed jousting battles while riding horses
Dynamic Physics - Damage and impact calculated from actual movement speed
Realistic Controls - Third-person camera with full body tracking
Stamina Management - Strategic resource management during combat
Visual Feedback - Lance breaking, camera shake, animations all provide clear combat feedback


🚀 Future Development Goals

 Tournament system with brackets
 More weapon types (swords, maces, etc.)
 Arena/map designs
 Scoring and leaderboard system
 Horse customization options
 Sound effects and music
 Team-based jousting modes


💻 Development Stack

Platform: Roblox Studio
Language: Luau (Roblox Lua)
Networking: RemoteEvents for client-server communication
Animation: Roblox Animation system
Physics: Roblox Physics Engine with custom calculations


📝 Development Notes
This project showcases:

Advanced camera systems in Roblox
Complex multiplayer synchronization
Physics-based combat mechanics
State management across client/server boundary
Performance optimization techniques

The camera system in particular demonstrates proper use of RenderStep, body part manipulation, and smooth client-side prediction while maintaining server authority for game logi

Built with Roblox Studio - Bringing medieval combat to life! ⚔️
