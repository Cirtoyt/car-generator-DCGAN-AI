# car-generator-DCGAN-AI

This is a basic implementation of a DCGAN ML algorithm thatcan generate retro/futuristic looking car images.
The algorithm trains two networks in parallel, a generator and a discriminator, where the discriminator aims to learn what a car looks like, then the generator aims to learn from the discriminator's judgement of how real or fake the images it produces are, iterating each epoch.

# Requirements

- Python 3.9
- PyTorch 1.7.1
- Matplotlib
- Numby
- os
- IPython.display's HTML
- - argparse
