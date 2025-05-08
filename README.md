# Quiz 8 – Imaging and Coding Technique Research

This file documents the design and technical research that supports the development of my individual animation for the final assignment in IDEA9103.

---

## Part 1: Imaging Technique Inspiration

My inspiration comes from *Volumes* by Maxim Zhestkov, an interactive particle-based animation where motion design and organic patterns merge through billions of colored particles. I’m particularly drawn to the way these particles flow and shift as if moved by invisible forces. I plan to incorporate this sense of fluid, user-driven movement by making each circular unit in *Wheels of Fortune* react to mouse position—modifying color, rhythm, or shape. This technique helps me enrich the visual rhythm and differentiate repeated elements through interaction, aligning with the assignment’s goal of creating diverse, animated responses.

📷 *Insert image here: Screenshot from Volumes or representative frame*

---

## Part 2: Coding Technique Exploration

To explore the interactive particle behavior inspired by *Volumes*, I found a p5.js sketch that creates dynamic particles in response to mouse input. Each particle is initialized with random `velocity`, `hue`, and `lifespan`, resulting in a constantly evolving, flowing animation. The code uses `mouseIsPressed` to generate new particles and `createVector()` to manage motion. It also sets `colorMode(HSB)` to enable vivid color changes and fading effects. I plan to adapt this technique to animate the circular units in *Wheels of Fortune*, enabling local movement and color variation as a response to user interaction.

🔗 [Sketch on OpenProcessing](https://openprocessing.org/sketch/2025005)

📷 *Insert image here: Screenshot of particle effect from the referenced sketch*

---

## File Notes

- This file is formatted using Markdown and should be committed to the GitHub repository.
- Ensure all images are included in an `images/` folder and linked using relative paths (e.g., `![caption](images/volumes.png)`).
- Commit message for submission: `Quiz 8`


