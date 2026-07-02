# I tweaked this viral prompt and made harder, it was fun watching all the models 

**Source:** https://x.com/IamEmily2050/status/2031159849669550385  
**Date:** Tue Mar 10 00:06:59 +0000 2026  
**Category:** System Prompts

---

I tweaked this viral prompt and made harder, it was fun watching all the models outcome, I did not any skill or system prompt to push the model's beyond the general avaliable setting.

[AESTHETICS & ATMOSPHERE] Act as a world-class creative technologist. Build an interactive 3D cloth simulation.
Theme: A discarded, glowing piece of evidence in a 1940s Noir Detective's office.
Environment: The background is a moody, rich mahogany wood color (#1a0f0a) fading into a heavy, dark vignette.
Lighting & Materials: Implement subtle WebGL shading. Use a cinematic setup: a warm, dim ambient light, and a harsh, invisible "desk lamp" (directional light) casting deep self-shadows across the folds of the paper.
Texture: The paper should look and feel like thick, tactile, yellowed cardstock. Generate procedural noise on the canvas texture to simulate rough paper grain.
[CHOREOGRAPHY & KINETICS] The interaction must feel weighty and incredibly satisfying.
Idle State: A subtle, barely noticeable breathing motion, like a draft in the room.
Interaction: On pointer drag, the paper must exhibit a snappy kinetic resistance. It is thick paper, so the bending constraints should be stiff—it folds, but doesn't stretch like rubber.
Release: When dropped, it should swing back and settle with a highly realistic, heavy dampening effect.
Cursor: Show a minimalist, glowing amber ring at the grabbed vertex.
[TECHNICAL ARCHITECTURE]
Rendering: Pure WebGL. Generate a 30x40 subdivided plane. Calculate normals dynamically.
Physics: Custom Verlet-integration mass-spring system. Pin the top row. Apply downward gravity. Integrate on every requestAnimationFrame.
Payload: Draw this text programmatically onto a hidden 2D canvas, then map it as the 3D texture using a vintage typewriter font (e.g., Courier): [CENTERED, BOLD]: L.A.P.D. EVIDENCE [LEFT ALIGN]: Case: #884-Black Dahlia [LEFT ALIGN]: Date: Oct 14, 1947 [DASHED LINE] [CENTERED]: "Meet me at the pier. [CENTERED]: Bring the files." [DASHED LINE] [BOTTOM RIGHT]: - V.
[STRICT BOUNDARIES]
Output exactly ONE fenced ```html code block containing everything.
Do not output any markdown text, greetings, or explanations outside the block.
Absolute Vanilla environment. Zero external dependencies, no React, no Three.js, no physics libraries.

Right Gemini Deep Think 
Left Gemini 3.1 pro on Gemini app
