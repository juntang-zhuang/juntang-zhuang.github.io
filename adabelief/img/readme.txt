### videos for optimization trajectory on toy examples.

Videos are in .mp4 format, and can be open with most video players. In case of display error, VLC Media player is recommended. (Link to VLC player: https://www.videolan.org/vlc/index.html)

Left of the video is the optimization process in 2D. For the ease of visualization, the global optimal point is at the bottom left corner of the blue cross, which is slightly different from the main paper where center of orange cross is the optimal.

Right of the video is the optimization process in 3D, and is synchronized with left window.

Note that the x-y plane is rotated between 2D and 3D plots. This is caused by the default of matplotlib library.

For all cases, with the same learning rate, AdaBelief reaches the optimal point faster than Adam and SGD.
