# TupperTransformer (A Novel Image Processing Algorithm)

> **Note**: This project is in a very early, experimental stage.

Welcome to my repository. This project is my exploration of a new image processing technique based on my 2018 preprint. Instead of manipulating a traditional grid of pixels, this algorithm operates directly on the high-precision integer (k value) used in Tupper's self-referential formula.

I am developing this into an interactive framework for image manipulation, and this repo serves as the implementation and demonstration of that research.

---

## 🚀 Live Demonstration

Check out the live demonstration of this algorithm to see it in action:

[**https://prathameshnium.github.io/TupperTransformer/**](https://prathameshnium.github.io/TupperTransformer/)

---

## The Core Algorithm (My Original Research)

The technical paper that this project implements is my 2018 preprint, which provides the complete mathematical foundation for these operations.

-   **Paper:** "Transformation of the pixels in Tupper's self-referential formula"
-   **Author:** Prathamesh Deshmukh (Me)
-   **Publication Date:** May 24, 2018

The core idea I explored in the paper is that any graphical formation plotted by Tupper's formula (in the $106 \times 17$ grid) can be transformed by applying arithmetic operations directly to the k constant.

### Key Transformations

This algorithm allows for precise transformations, including:

-   **Pixel Manipulation:** Add or remove any individual pixel `i` by adding or subtracting the value $17 \times 2^{i-1}$ from the k constant.
-   **Spatial Translation (Moving):**
    -   **Up/Down:** Move the entire image `n` pixels up or down by multiplying or dividing `k` by $2^n$.
    -   **Left/Right:** Move the entire image `n` pixels left or right by multiplying or dividing `k` by $2^{n \times 17}$.
-   **Animation:** Apply transformations sequentially to create a "film" or "motion picture," where each new `k` value represents a single frame.
-   **Complex Transformations:** Apply different transformations to different pixels simultaneously or create diagonal movements.

## How to Use

Visit the demonstration website to see the algorithm in action.

1.  Enter a `k` value (or load one of the examples from my paper, such as Tupper's formula, the centered UFO, the top-left UFO, or the Tetris scene).
2.  Apply transformations using the control buttons.
3.  See the resulting `k` value and the updated image in real-time.

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

For a full list of publication details, indexing, and archive links, please see the CITATION.md file in this repository.