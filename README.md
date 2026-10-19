# Documentation layout comparisons for issue #8281

Before: only the middle Grid track's minmax lower bound is set to 0.
After: main min-width: 0, scrollable tables, and wrapping prose inline code.

All screenshots use Microsoft Edge 155.0.4283.62 at device scale 1 and a 700px viewport height. Each pair uses the same viewport width and visible content anchor.

The after table screenshots show the table scrolled to its last column; the root page remains at scrollX = 0. The inline-code pair uses the live SSO guide, which is not part of the repository docs generator. See measurements.json for details.

These images are hosted on a separate branch and are not part of the fix branch's pull request diff.
