# ethesis-template
The latex template for my PhD thesis at ETH Zurich.

Distributed under the MIT License
Copyright (c) 2017 Jonathan Binas


# What does it provide?

The jb-thesis class provides some carefully designed typographic and stylistic features, such as hanging section numbers and illustrated part headers. See the compiled example.pdf for an overview.


# Prerequisites

## Fonts

The class has been designed based on the Charter font family for the body text and math (use mathdesign package with the charter option enabled), and Source Sans Pro for headers and other sans-serif type, so

 * Bitstream Charter (free) or ITC Charter (commercial),
 * Adobe Source Sans Pro

should be present on the system. The class might work well with other fonts, but has only been tested with the ones mentioned above.

Even though the document will compile without, it is highly recommended that the

 * microtype package

be installed for improved typesetting (will be loaded and used by the class automatically, if present).

## Additional packages

The following additional packages are required to compile the example, but might not necessarily be required for your own document.

 * amsmath, amsthm
 * mathtools
 * algorithm2e
 * upgreek
 * graphicx, xcolor
 * tikzpagenodes
 * cleveref
 * blindtext

## Revision info

The class supports printing of the current git revision (see example.pdf). This can be very useful to relate drafts that are being distributed to a particular revision. For this to work, the

 * gitinfo2 package

needs to be present, and the post-{commit,checkout,merge} hook from http://ctan.mirror.rafal.ca/macros/latex/contrib/gitinfo2/post-xxx-sample.txt should be added to your .git/hooks/ directory.

