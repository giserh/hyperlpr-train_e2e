# hyperlpr-train_e2e
A simple code for creating licence plate images and train e2e network based on HyperLPR https://github.com/zeusees/HyperLPR.

Usage:
The image size created automatically is 120 * 30, fix the input size when you use the e2e network. You can create and train your own e2e network if you want.

Also, when tested in real scene, the e2e network performs not very well due to that the images' quality created automatically are still poor. If you have real image dataset and labels, it may be perfect.

Attention:
Change the path when you run these code. For some fonts and templates when generating images, please refer to https://github.com/szad670401/end-to-end-for-chinese-plate-recognition
