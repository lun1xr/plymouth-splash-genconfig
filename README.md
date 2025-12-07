# plymouth-splash-genpatch
**Important Note: This repo is the source for the AUR package and is not meant to be run as-is**

A tool for generating plymouth bootsplash animations from video or gif files. Will patch Plymouth's two-step to run at the proper framerate.

For optimal output, use relatively small files as the entire content of the animation must be loaded into the initramfs. As a general rule, the longer and higher resolution the graphic is, the lower the framerate must be to maintain a relatively fast boot. 

In the future I may add a tool to compress/optimize the files automatically, but for now whatever you use as input will be replicated unmodified.
