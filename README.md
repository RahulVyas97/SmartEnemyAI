Smart Enemy AI: Souls-like Boss Battle Prototype
An Unreal Engine action-RPG demo featuring a dynamically adaptive enemy AI that responds to player combat styles in real-time.

🎮 Project Overview
This project is a technical prototype exploring the intersection of Souls-like strategic difficulty and Hack-and-Slash visual combo mechanics. The core of the project is a "Smart AI" boss capable of analyzing player behavior—switching between aggressive and defensive stances based on distance and the player's offensive pressure.

🛠️ Technical Highlights

•	Adaptive AI Architecture: Built using Unreal Engine Behavior Trees and Blackboards to manage complex state transitions (Idle, Patrol, Pursuit, Attack, and Retreat).

•	Environment Query System (EQS): Utilized for intelligent positioning, allowing the AI to evaluate the arena for optimal tactical advantages.

•	Dynamic Combat System: * AI Perception: Implemented a perception system for real-time player tracking and reaction.
  
    o	State-Based Logic: The AI transitions between states based on player aggression levels, utilizing specialized "BPC_Attacks" components for varied patterns.
    
    o	Advanced Player Mechanics: Includes a target-lock system, stamina-managed combos, and frame-specific parry/dodge windows.

•	Damage & Interaction: Custom interface-based damage system with sphere-trace collision detection and physics-driven "ragdoll" death responses.

🚀 Key Features

•	Intelligent Strategy Switching: AI detects if the player is using long-range or melee tactics and adjusts its approach accordingly.

•	Visually Rich Combat: Blends high-intensity animations (montages) with technical gameplay depth inspired by Dark Souls and Devil May Cry.

•	Performance Balanced: Designed to provide a "tough but fair" challenge by balancing AI unpredictability with clear player feedback.

💻 Tech Stack

•	Engine: Unreal Engine (Third-Person Template base) 

•	Blueprints: Advanced Character & AI Blueprints, Animation Blueprints (ABP) 

•	AI Tools: Behavior Trees, Blackboards, AI Controllers, Perception System, EQS 

•	VFX/SFX: Integrated Niagara effects and spatialized sound design for immersive combat 

📖 Lessons Learned (Dissertation Research)
This project served as the practical component of my Master’s dissertation. Through user surveys and iterative testing, I learned that:

•	Players find high satisfaction in AI that "reads" their moves, provided the difficulty remains fair and not purely punishing.

•	The integration of Hack-and-Slash combos into a Souls-like framework requires careful stamina balancing to maintain strategic depth.

