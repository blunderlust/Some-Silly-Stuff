# Higher-Dimensional UFO Geometry Explorer

**An interactive 4D/5D mathematical thought experiment inspired by familiar reported UFO silhouettes.**

This standalone browser app explores a question: **Could a three-dimensional silhouette be the projection or cross-section of an object with additional spatial dimensions?**

It is an educational geometry visualization, **not a reconstruction of a real craft, a UFO detection tool, or evidence of extra-dimensional technology**. A single observed 3D shape does not uniquely determine a 4D or 5D original. Many different higher-dimensional objects can produce similar lower-dimensional appearances.

## Launch

Open **[index.html](./index.html)** in any modern browser. No installation, account, server, internet connection, or external libraries are required. It is designed to work on desktop and mobile.

## What you can explore

- **Four starting silhouettes:** tic tac/cigar, disc/saucer, triangle, and sphere/orb.
- **Higher-dimensional rotations:** X–W and Z–W, and (in 5D mode) X–V and W–V.
- **Two different visualizations:** a projection of the complete mathematical object into visible 3D and a thin sampled 3D *cross-section* at a chosen hidden-axis location.
- **Hidden-axis extent:** vary how much of the hypothetical object lies along its unseen dimensions.
- **Animation:** automatically rotate the model and observe changing appearances.

The colors indicate position along the hidden **W** coordinate; they do not represent actual materials or emitted light.

## Mathematical approach

For the tic tac, saucer, and orb models, the starting object is a 4D ellipsoid:

```text
(x/a)^2 + (y/b)^2 + (z/c)^2 + (w/d)^2 <= 1
```

The visible axis scales **a, b, c** approximate a familiar silhouette, while **d** is an independently chosen extent along the fourth spatial axis. The triangle uses a 3D triangular prism extended along **W**. Adding a fifth spatial dimension **V** generalizes the construction.

The program samples points in the higher-dimensional solid, rotates them using coordinate-plane rotation matrices, and displays them on a 2D canvas through sequential perspective views. The right pane approximates an intersection by filtering points near a chosen W value (and V≈0 in 5D mode). Apparent holes or irregular boundaries may be finite-sampling artifacts.

**These are extra spatial dimensions, not time as the fourth spacetime coordinate.** The display is a mathematical rendering, not a physical theory of light propagation or radar returns in higher-dimensional space.

## Important limitations

- The inverse problem is **underdetermined**: a 3D projection does not identify its unique 4D/5D cause.
- The models are **illustrative choices**; the shapes do not come from measured UAP data.
- A geometric projection is different from a physical observation. Whether hypothetical higher-dimensional matter would be visible in this way is unknown.
- The app uses finite point samples and a slice tolerance, so the diagrams are approximate.
- Ordinary 3D rotation, camera perspective, optical effects, and other explanations must be considered before attributing an observation to extra dimensions.

## A useful follow-up experiment

Try fitting **one** higher-dimensional shape to *several* observed 3D silhouettes across different rotations or slice positions. Such a fit would demonstrate mathematical compatibility, **not** establish that any UAP actually has extra spatial dimensions.

## Project status

Single-file, dependency-free interactive prototype for curiosity and education.
