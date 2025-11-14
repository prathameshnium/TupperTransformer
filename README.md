# TupperTransformer (A Novel Image Processing Algorithm)

> **Note**: This project is in a very early, experimental stage.

Welcome to my repository. This project is my exploration of a new image processing technique based on my 2018 preprint, "Transformation of the pixels in Tupper's self-referential formula."

This algorithm operates directly on the high-precision integer (k-value) used to generate Tupper's self-referential bitmaps, rather than manipulating the pixels after they are rendered. This repository contains the interactive demo that serves as the proof-of-concept and implementation of that research.

---

## 🚀 Live Demonstration

Check out the live, interactive demo to see this algorithm in action:

My research paper is based on Tupper's self-referential formula. While popular for its ability to plot itself, its true power is that it can plot *every* possible combination of pixels in a $106 \times 17$ grid. The `k` value effectively acts as a slider across this infinite bitmap.

My research idea started with a question:

> "If there is some graphical formation at a particular value of k, then what can be done to change the graphical formation or to change its position?"

This question led to two main ideas:
1.  How to change any graphical formation into another by applying arithmetic operations directly to the `k` value.
2.  How these different graphical formations can be used as frames to create a film or motion picture.

### What can my research do?
-   Represent all possible graphical formations (within 1802 pixels) and all their possible variations.
-   Create a formula for any film or motion picture.
-   In short, my research represents a mathematical form of the "Library of Babel" but for film and motion pictures.

---

## About the Demo (Instructions)

The interactive demo brings these concepts to life with a simple, tabbed interface.

### 1. Transform & Load (Main Panel)
This is the main editor. You can:
-   **Load Examples:** Load the classic "Tupper's" formula or the "UFO (Center)" image.
-   **Transform:** Use the "Full Transform" buttons (Up, Down, Left, Right, Diag) to modify the entire image.
-   **Animate:** Click and hold any transform button to create a temporary animation. If you hold for 1 second, the animation will "latch" and continue playing, allowing you to release the mouse. A "Stop" button will appear.

### 2. Draw
This panel demonstrates the reverse of the formula:
-   Click or drag on the canvas grid to toggle pixels on or off.
-   The K-Value in the text box will update in real-time, showing you the exact integer that represents your drawing.
-   Use "Clear Canvas" to set `k` to 0.

### 3. Demos & Examples
This tab showcases the two major examples from the paper:
-   **Animation Demo (Eg3.1):** Click "Play UFO Animation" to see the "Top-Left UFO" from the paper animated using the $k^{n}= k\times2^{n\times17}$ formula.
-   **Interactive Tetris (Eg3.2):** Click "Load Tetris Example" to load the scene. The "Piece" buttons will only move the "L-piece" (`ks`) while leaving the resting pieces (`kr`) untouched, demonstrating the "Different transformation on the individual Pixar" concept.

---

## Citation

If you use this work, please cite the original preprint.

**Formatted Citation (APA Style):**
> Deshmukh, P. (2018). *Transformation of the pixels in Tupper's self-referential formula*. Figshare. https://doi.org/10.6084/m9.figshare.6373046

**BibTeX Citation (Recommended):**
```bibtex
@article{Deshmukh2018,
  author = "P Deshmukh",
  title = "{Transformation of the pixels in tupper's self-referential formula}",
  year = "2018",
  month = "6",
  url = "https://figshare.com/articles/preprint/Transformation_of_pixels_pdf/6373046",
  doi = "10.6084/m9.figshare.6373046.v2"
}
```

For a full list of publication details, indexing, and archive links, please see the `Publication_History.md` file in this repository.

For a full list of publication details, indexing, and archive links, please see the CITATION.md file in this repository.
---

History & Related Materials
## History & Related Materials

History
### History
-   **2018-06-08:** First online & posted date.

2018-06-08 - First online date, Posted date

Related Materials

Tupper's Self-Referential Formula Explained

Tupper's Formula Tools (defunct)

Numberphile: The 'Everything' Formula

Tupper's Original Paper (Self-Referential Formula)
### Related Materials
-   Tupper's Self-Referential Formula Explained
-   Tupper's Formula Tools (defunct)
-   Numberphile: The 'Everything' Formula
-   Tupper's Original Paper (Self-Referential Formula)