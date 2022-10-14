# theapa.bst-fixed

In tex, it is common to use `@article` to reference arxiv, or publications without a `volume` attribute.
The `theapa.bst` is used in many journals (e.g., JAIR), and cannot handle missing `volume`s.

This repo is a tentative to fix this, and fix the long list of compilation errors that comes when the conditions above are met.
You can find the fix is at [this commit](https://github.com/epignatelli/theapa.bst-fixed/commit/613d478bc296776f471919be9a15a13937c85fd8).
