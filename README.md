Balloon Story

Balloon Story is a browser-based physics simulation and game focused on the mechanics of the balloon's ascent. The project uses a custom-tuned physics engine to simulate the journey of a buoyant object through five distinct atmospheric layers, each with varying gravitational and environmental constraints.

Gameplay Mechanics

The primary objective is to maintain flight and navigate environmental hazards.

Input Controls

    Touch Devices: Tap the balloon to apply upward force. The horizontal vector is determined by the relative position of the tap to the object's center.

    Desktop/Laptop: * Mouse/Trackpad: Click the balloon to apply force.

        Spacebar: Initialize the simulation from the start menu.

        'M' Key: Trigger the menu or terminate the current session.


Operational Modes

    Standard Mode: High-stakes flight where collisions with obstacles result in session termination. Persistent high scores are recorded exclusively in this mode.

    Invincible Mode: A non-terminating flight mode for testing physics or low-stress navigation. High scores are disabled to maintain competitive integrity.


Technical Specifications

The Physics Engine

The simulation is built on a set of hard-coded constants designed to provide a specific tactile weight to the balloon.

    Base Gravity: 0.24

    Standard Tap Power: −8.8

    Odometer Wind System: A distance-based trigger logic. Rather than scheduling events by time or static score points, the engine monitors "points traveled" since the last environmental event. A new gust or solar flare is triggered every 8–16 points.


Biome Progression

The environment shifts dynamically based on altitude (score milestones), affecting gravity and obstacle types.

Region	Milestone	Gravity	Hazards

Park Wanderer	0+	0.24	Low-density birds

Urban Voyager	15+	0.22	Urban architecture, high-velocity birds

Peak Seeker	35+	0.20	High-altitude eagles

Astronaut	60+	0.18	Satellites, Solar Flares

Exosphere	100+	0.12	Persistent Satellites, increased horizontal drift
