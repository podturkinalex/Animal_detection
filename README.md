# Animal_detection
Here I worked with camera trap data from the Reconyx Camera Trap data set.
There are 20 animal species of different sizes, so it was necessary to choose a model that will cope with the challenge of detecting and determining the class of even small objects.
'Faster RCNN` model with the backbone `resnet50_fpn` was chosen for the fine-tuning.
According to the "Weakly Supervised Faster-RCNN+FPN to classify animals in camera trap images" paper (https://arxiv.org/pdf/2208.14060.pdf) this model is more suitable for small objects on camera trap data.

Source: `Reconyx Camera Trap data set`. X. Yu, J. Wang, R. Kays, P. A. Jansen, T. Wang, and T. Huang,
“Automated identification of animal species in camera trap images,” EURASIP Journal on Image and Video Processing, vol. 2013, no. 1, p. 52, 2013. https://jivp-eurasipjournals.springeropen.com/articles/10.1186/1687-5281-2013-52

Data were downloaded from https://borealisdata.ca/dataset.xhtml?persistentId=doi:10.5683/SP/TPB5ID
