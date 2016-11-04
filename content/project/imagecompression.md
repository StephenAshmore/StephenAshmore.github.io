+++
date = "2016-09-19T16:20:36-05:00"
repo = ""
title = "Image Compression"
Description = "Compressing Images using Neural Inference and Neural Networks"
Thumb = ""
+++

Image Compression is a useful tool to save disk space, and computation speed. JPG is a great example of a popular image compression technique. However, can we do better with a machine learning technique like neural networks? I'm playing around with neural networks to see how well a technique I call neural inference can compress an image. A few caveats, it will probably be much slower than JPG. Depending on the implementation, you could end up using a lot of "feed forwards" to generate the uncompressed version of the image, and that is just not good for displaying an image. Users demand super fast display of images, and neural networks may not be the best here.
