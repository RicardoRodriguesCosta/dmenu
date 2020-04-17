# Luke's dmenu

Extra stuff added to vanilla dmenu:

- reads Xresources (ergo pywal compatible)
- alpha patch, which importantly allows this build to be embedded in transparent st
- can view color characters like emoji (libxft-bgra is required for this reason)

## Installation

You must have `libxft-bgra` installed until the libxft upstream is fixed.

After making any config changes that you want, but `make`, `sudo make install` it.
