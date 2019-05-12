# SunGan
A GAN to try and train AIA EUV Images to perform full disc prediction of these images.

I have been working on using AIA data from solar wind prediction to understanding nanoflares (the codes for which will come in some time!). Sometimes, however, I would simply want to play with the data and see what stuff can be done. This work is something similar.

I thought to myself -- why not give in one day of AIA EUV data, and predict what the next day might look like? For this, I used a GAN to produce the images. The visualizer notebook has been attached for referece, and the actual network class files will be made available on request. The notebook can be run on the very awesome Google Colab!

The primary result is this: The Generator captures solar rotation, and just shifts the image accordingly. Thus, the 'evolution' of features is not something seen from this training exercise. Still, it is a nice change of work for me!

The code is of course, under construction. I will be happy to have people contribute to this, or myself contribute to a similar work!
