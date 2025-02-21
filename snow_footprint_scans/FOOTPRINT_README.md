# Notes about these images:

Due to the way these images were rendered, they need to be normalized.

Also, the images are 4K with the idea that subsets of the image could be sampled to create lower-resolution stamps.

Code to do that will hopefully end up here, but since it is not part of the C++ code base, I am wondering if it should be put somewhere else.

# Animated stamps

Currently, the individual images are stored in `snow_footprint_scans/stamp_animation/` and are formatted as `%04d.png`.
