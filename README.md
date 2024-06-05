# Useful TouchDesigner Toxes

A bunch of helpful Touchdesigner toxes that I use for performances, all toxes are created from free tutorials available on YouTube and packaged as toxes with exposed parameters for ease of performance. Would suggest hosting each tox in an Engine COMP to parallel process the effects when chaining them.

All toxes were created in **TouchDesigner 2023.11600** 

---

### Abstract Fluid

This was created using Daniel Steenhoff's Abstract Fluid Simulation [tutorial](https://youtu.be/e7K_UX7KUzw?si=yD1NMHpKIbaQbYpN) and modified to accept a video feed.

**Parameters**

1. Reset         - Resets the internal feedback
2. Dry/Wet       - Blends between clean and processed video
3. Edge Strength - Adjusts the strength of the internal edge TOP
4. Source Gain   - Adjusts the gain of the clean signal
5. Feedback Gain - Adjusts the amount of feedback
6. Recolor       - If turned on recolors the effect using a ramp TOP that is referenced down below

---

### Circuit Bending

Derived from Elekktronaut's Circuit Bending [tutorial](https://youtu.be/mAp_wxuuw_U?si=fhbUI_IYPV3CMHKR) and modified with exposed performance parameters.

**Parameters**

1. Reset     - Resets the internal feedback
2. Dry/Wet   - Blends between clean and processed video
3. Distort   - Applies distortion to the feed
4. Jitter    - Applies a jitter
5. Y-Glitch  - Randomly moves the whole feed in the Y-axis
6. Recolor   - Enables the recolor lookup
7. ColorSeed - Changes the color applied to the feed
8. BlendMode - Changes the blending mode for the Composite TOP

---

### Datamosh

Derived from Paketa12's Datamoshing [tutorial](https://youtu.be/_MJ71LyBAjk?si=gYGUDhvqfadwzNZt) and modified to accept any aspect ratio with exposed performance paramters.

**Parameters**

1. Reset          - Resets the internal feedback
2. Dry/Wet        - Blends between clean and processed video
3. Monochrome     - Desaturates the incoming signal, works independently of the Datamosh network
4. Invert         - Inverts the colors of the incoming signal, works independently of the Datamosh network
5. Contrast       - Increases the contrast of the incoming signal, works independently of the Datamosh network
6. Mosh Spread    - Controls the amount of spread in the Datamosh
7. Mosh Speed     - Controls the speed of the mosh effect
8. Mosh Gain      - Controls the amount of datamoshing
9. Mosh Direction - Controls the direction of the datamoshing

---

### Falling Liquid

Derived from pppanik's Liquid Image Displacement [tutorial](https://youtu.be/Z8B-N_pvLis?si=R4IQHecMju8qHAjl)

***Parameters**

1. Reset          - Resets the effect
2. Dry/Wet        - Blends between clean and processed video

---

### Feedback

An implementation of feedback, created by me

**Parameters**

1. Reset          - Resets the internal feedback
2. Dry/Wet        - Blends between clean and processed video
3. Scale          - Changes the scale of the signal in the feedback loop
4. Translate      - Changes the translation of the signal in the feedback loop
5. Brightness     - Changes the brightness in the feedback loop
6. Opacity        - Changes the opacity in the feedback loop

---

### Pixel Sorting

Derived from Elekktronaut's Pixel Sorting [tutorial](https://youtu.be/xasLIEw23zY?si=bu1Yu7ebxYxDg8Oy) and exposed parameters for performance

**Parameters**

1. Enable      - Enables/Disables the effect
2. Reset       - Resets the effect
3. Amount      - Changes the speed of the effect
4. Direction   - Changes the direction the sorting appears in

---

### Random Number

An implementation to create random numbers, set to a pulse or through an internal frequency, created by me

**Parameters**

1. Internal Pulse    - Enables the internal LFO to generate a number, if disables, a pulse can be sent into the input to generate a number
2. Frequency         - Sets the frequency at which a random number is generated
3. Seed              - Sets the seed for the noise of the number generation
4. Range             - Can scale the output

---

### Random Rectangle Composite

Simple effect that takes in your signal and masks it into two rectangles created randomly

**Parameters**

1. Enable    - Enables/Disables the effect
2. Randomize - Randomizes where the rectangles are made

---

### Reaction Diffusion

An implementation of Ben Heim's Reaction Diffusion [tutorial](https://youtu.be/JSp9AQ_wBZw?si=4mI2288_Mpypv24A) with exposed parameters for performance

**Parameters**

1. Reset          - Restarts the animation
2. Resolution     - Sets the resolution of the system
3. Blur 1         - Changes the size of the birth
4. Shrink 1       - Changes the size of the birth
5. Blur 2         - Changes the size of the end
6. Shrink 2       - Changes the size of the end
7. Sharpen        - Adds sharpening in the feedback loop
8. Feedback Edge  - Adds the feedback edge effect which gives it the sense of movement
9. Speed          - Changes the speed of the animation
10. Feedback Gain - Changes the amount of feedback in the chain

---

Have fun!





