# Similar Image Classifier

## 1. Transfer learning

we will build a similar images finder by dissecting the trained weights of the image object-classifier VGG and using it to extract feature vectors from an image database to see which images are “similar” to each other. This technique is called transfer learning and requires no training on our end — the hard work was done back in the day when VGG was actually being trained, we are just re-using the trained weights to build a new model.
