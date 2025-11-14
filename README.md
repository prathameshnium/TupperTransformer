# TupperTransformer (A Novel Image Processing Algorithm)

<p align="center">
  <a href="License"><img alt="GitHub" src="https://img.shields.io/github/license/Prathameshnium/TupperTransformer"></a>
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/Prathameshnium/TupperTransformer">
  <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/Prathameshnium/TupperTransformer">
</p>

> **Note:** This project is in a very early, experimental stage.

Welcome to my repository. This project is my exploration of a new image processing technique based on my 2018 preprint, "Transformation of the pixels in Tupper's self-referential formula."

This algorithm operates directly on the high-precision integer (k-value) used to generate Tupper's self-referential bitmaps, rather than manipulating the pixels after they are rendered. This repository contains the interactive demo that serves as the proof-of-concept and implementation of that research.

## Live Demonstration

Check out the live, interactive demo to see this algorithm in action:

https://prathameshnium.github.io/TupperTransformer/

## About the Paper (Algorithm Summary)

My research paper is based on Tupper's self-referential formula, which is popular due to its property of plotting itself. But that is not the only amazing thing about this formula: it doesn't only plot itself, but it plots every possible combination of the $106 \times 17$ pixels.

A copy of the paper is also available in this repository in the [`paper`](./paper) directory.

I.e. it plots all possible combinations of these 1802 pixels, and the value of k is used for sliding over the y-axis.

My research idea started with a question:

> "If there is some graphical formation at a particular value of k, then what can be done to change the graphical formation or to change its position?"

This question leads to my research, which has two main ideas:

1.  How to change any graphical formation into another graphical formation by applying some kind of operation to the value of the k.

2.  How this different graphical formation can be used as a frame to create a film or motion picture.

### What can my research do?

My research can do the following:

-   Represent all possible graphical formations (within 1802 pixels) and all their possible variations.
-   Create a formula for any film or motion picture.

In short, my research represents a mathematical form of the "Library of Babel" but for film and motion pictures.

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
-   Use "Clear Canvas" to set k to 0.

### 3. Demos & Examples

This tab showcases the two major examples from the paper:

Animation Demo (Eg3.1): Click "Play UFO Animation" to see the "Top-Left UFO" from the paper animated using the $k^{n}= k\times2^{n\times17}$ formula.

Interactive Tetris (Eg3.2): Click "Load Tetris Example" to load the scene. The "Piece" buttons will only move the "L-piece" (ks) while leaving the resting pieces (kr) untouched, demonstrating the "Different transformation on the individual Pixar" concept.

## Citation

If you use this work, please cite the original preprint.

### Formatted Citation (APA Style)

> Deshmukh, P. (2018). *Transformation of the pixels in Tupper's self-referential formula*. Figshare. https://doi.org/10.6084/m9.figshare.6373046

### BibTeX Citation (Recommended)

```bibtex
@article{Deshmukh2018,
  author  = "P Deshmukh",
  title   = "{Transformation of the pixels in tupper's self-referential formula}",
  year    = "2018",
  month   = "6",
  url     = "https://figshare.com/articles/preprint/Transformation_of_pixels_pdf/6373046",
  doi     = "10.6084/m9.figshare.6373046.v2"
}
```

For a full list of publication details, indexing, and archive links, please see the CITATION.md file in this repository.

## History & Related Materials

### History

-   **2018-06-08** - First online date, Posted date

### Related Materials

-   [Tupper's Self-Referential Formula Explained](https://www.petervis.com/mathematics/tuppers_self-referential_formula/tuppers_self-referential_formula.html)
-   [Tupper's Formula Tools (defunct)](http://tuppers-formula.tk)
-   [Numberphile: The 'Everything' Formula](https://youtu.be/_s5RFgd59ao)
-   [Tupper's Original Paper (Self-Referential Formula)](http://campus.lakeforest.edu/trevino/Tupper_Paper.pdf)

## Technologies Used

The interactive demo is built with standard web technologies:

-   **HTML5:** For the structure of the web page.
-   **CSS3:** For styling the user interface.
-   **JavaScript (ES6+):** For the core logic of the TupperTransformer algorithm and user interactions.
-   **BigInt:** Natively handled in modern JavaScript for the high-precision integer arithmetic required for the k-value.

## Project Structure

The repository is organized as follows:

```
.
├── paper/
├── CITATION.md
├── index.html
├── License
├── README.md
```

-   `paper/`: Contains the original 2018 preprint that this project is based on.
-   `index.html`, `style.css`, `script.js`: The core files for the interactive web demo.
-   `CITATION.md`: Provides detailed citation information for academic use.
-   `License`: The MIT license for the project.
-   `README.md`: This documentation file.


## Contributing

I am open to suggestions and collaborations. If you have any ideas or would like to discuss implementing this research, please feel free to open an issue to start a conversation.

## License

This project is licensed under the MIT License - see the [LICENSE](License) file for details.

## Categories & Keywords

*(From Figshare)*

### Categories

-   Theory of computation 
-   Applied computing 
-   Image processing
-   Applied mathematics 

### Keywords

-   tuppers-formula
-   tuppers-self-referential-formula
-   image-processing
-   algorithm
-   math
-   theory-of-computation
-   applied-computing
-   applied-mathematics
-   computation-theory
-   applied-computer-science
-   javascript
-   interactive-demo
-   preprint
-   bigint