# Gameplay Systems & Mechanics

## 1. The Grid (Strategic Layer)
The game takes place on a top-down 2D map representing a suburban neighborhood.
* **Nodes:** Interactive points representing individual cameras, smart-lights, or sensors.
* **Digital Noise:** Areas not covered by an active camera are shrouded in a specialized "Fog of War."

## 2. System Power (Resource Management)
* **Passive Drain:** Keeping cameras active slowly consumes the power supply.
* **Active Burst:** Triggering environmental objects (sprinklers, alarms) costs a significant energy chunk.
* **Low-Power Mode:** Power recharges only when the operator enters this mode, which temporarily blinds them to enemy movements.

## 3. The Citizen (AI Agent)
The Citizen is an autonomous agent who moves toward their home node but is influenced by:
* **Fear:** Increases in darkness or near strange noises, leading to uncontrollable "Panic Sprints."
* **Safety:** Fear levels decrease when the Citizen is in well-lit areas.

## 4. The Shadows (Antagonists)
* **Behavior:** These entities actively avoid light sources and are attracted to loud noises.
* **Interaction:** They do not attack the player; they "consume" the Citizen upon entering the same tile, resulting in immediate mission failure.

## 5. Interactables
* **Car Alarms:** Attract Shadows but significantly increase Citizen fear.
* **Smart Sprinklers:** Create "Noise" barriers that Shadows cannot cross.
* **Electronic Locks:** Can trap Shadows in structures but require constant power to remain active.
