# House Style

This is CDIG's cross-project CSS framework.

## What belongs in House Style?

It should eventually include a few things:

1. Reset / Normalization styles — filtered down to just the stuff we care about based on the browsers we support and the HTML elements we actually use.
2. Colors — brand colors, semantic colors, and other common colors
3. Components — buttons, inputs, layout, typography, and other stock UI pieces

The stuff is House Style is the stuff that should be presented consistently across all our projects.

## Issues and impediments

There are a few things that make this project a little difficult to work on.

1. Existing projects can't have their core styles extracted without breakage, due to dependency on source order or specificity.
2. It'd be nice to do things quite differently — but if we go that route, that will require new stuff and old stuff coexisting, which is finicky.
3. It'd be nice to use some of the futuristic features of CSS (like `color-mod()` and `lch()`), but those won't be ready for a few years yet.
