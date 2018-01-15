# appendixnumberbeamer.sty

This package fixes the frame numbering in `beamer` when using an appendix
such that the slides of the appendix are not counted in the total frame
number of the main part of the document. The total frame number counter
is reset to 0 when entering the appendix.

The standard usage is to include `\usepackage{appendixnumberbeamer}` in
the preamble and then declare the beginning of the appendix as usual
using the `\appendix` command.

This package is also available from
http://www.ctan.org/pkg/appendixnumberbeamer and is included in the
TeXLive and MiKTeX distributions