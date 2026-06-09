# Cubathon (My First Unity Game)

A simple 3D runner game built in Unity. This is my very first project learning game development, focusing on physics, player input, and basic game loops.

## Gameplay
* **Objective:** Control a red cube sliding down a track and avoid colliding with the obstacle cubes.
* **Game Over:** If you collide with an obstacle, the player stops moving.

## Controls
* **Forward Movement:** Automatic constant physics force.
* **Steering:** Use the **Right and Left Arrow** key to move.

## Features & Mechanics Learned
* **Physics-Based Movement:** Utilizing `Rigidbody.AddForce` inside `FixedUpdate` for consistent movement physics.
* **Input System:** Implementing Unity's New Input System to detect real-time keyboard presses.
* **Linear Damping:** Adjusting drag to ensure snappy movement controls and preventing the player from sliding like they are on ice.
* **Version Control:** Setting up a proper `.gitignore` file to manage Unity project sizes cleanly on GitHub.

## Built With
* **Game Engine:** Unity (2022+)
* **Language:** C#
