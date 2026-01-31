# Technical Specifications & Logic

## 🖥️ Surveillance UI Architecture
The game is designed for a "Diegetic UI," meaning the interface is built to look like actual surveillance software.
* **Visual Filters:** Grainy camera overlays, scanlines, and monospaced technical fonts.
* **Information Limitation:** Success is measured by the player's ability to predict AI reactions despite limited visual data.

## 🔊 Audio Logic
* **Binaural Cues:** Used to help the player track Shadow movement direction when they are outside of a camera's field of view.
* **Audio Sensors:** In "Dead Zones" (alleys with no cameras), players must rely entirely on rhythmic audio spikes to locate threats.

## 🛠️ Pathfinding & AI
* **Influence Mapping:** The environment uses a weight-based system where light nodes attract the Citizen and noise nodes attract Shadows.
* **Panic State:** A specialized state override for the Citizen AI that ignores optimal pathing in favor of erratic movement when Fear is maxed.
