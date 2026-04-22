# CARLA 2026 Quantum Simulator Architecture Paper

This directory contains a Springer LNCS draft for the architecture-focused CARLA paper.

Build:

```sh
latexmk -pdf main.tex
```

Scope:

- Architecture only: compressed state-vector storage, block layout, selective decompression, LRU cache, and reversible lossless compression flow.
- No experimental performance claims. Implementation details and results are reserved for a companion paper.
- Bundles the official downloaded Springer LNCS `llncs.cls` class and `splncs04.bst` bibliography style from the CARLA template folder.
