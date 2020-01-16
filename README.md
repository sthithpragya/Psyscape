# Psyscape
Using CycleGAN to learn psychedelic art style and generate landscapes

This is an implementation of a CycleGAN to learn the art style of psychedelic art found over the internet and render photographs of landscape and nature in that art-style.

First extract the images in input and then train the network by executing the main.py file.

You can adjust the number of epochs (for which the network can be trained) and other parameters from the main.py file itself.

Training for different epochs translates to the network learning different styles. For reference, you may see some of the generated landscape images corresponding to different epochs in the generated_art folder.

Post learning, you can add any custom 256x256 landscape image and render it using the trained weights of the network by setting test = True in main.py.

For more details, read the project report.
