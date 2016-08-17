# latex-grant

LaTeX classes for formatting scientific documents, including grant proposals.
* `grants`: Base class for formatting grant proposals
* `arl`: Army Research Laboratory
* `darpa`: Defense Advanced Research Projects Agency
* `doe`: Department of Energy
* `nih`: National Institutes of Health
* `nrl`: Naval Research Laboratory
* `nsf`: National Science Foundation
* `onr`: Office of Naval Research

## Installation
The package is available through TeX Live and MikTeX as `grant`.

## Example usage
```
\documentclass{nsf}

\addbibresource{Bibliography.bib}

\begin{document}

\chapter{Project-Summary}
...

\chapter{Project-Description}
...

\chapter{Bibliography \& References Cited}
\printbibliography[heading=none]

\end{document}
```

## License
The example model is released under the [MIT license](LICENSE).

## Development team
`latex-grant` was developed by [Jonathan Karr](http://www.karrlab.org) at the Icahn School of Medicine at Mount Sinai in New York, USA.

## Questions and comments
Please contact the [Jonathan Karr](http://www.karrlab.org) with any questions or comments.
