# Unexpected Flexbox Container Expansion in Tailwind CSS

This repository demonstrates a subtle bug in Tailwind CSS involving flexbox containers and overflowing content.  When inner elements within a flex container have content that exceeds their allocated width (using classes like `w-1/2`), the container itself unexpectedly expands horizontally.

This can be problematic when attempting to create fixed-width layouts. The provided solution shows how to properly handle this using the `flex-shrink-0` utility class to prevent the expansion.

## Setup

1. Clone this repository.
2. Open `bug.html` to see the problematic behavior.
3. Open `solution.html` to see the corrected behavior.
