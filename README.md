# amazon-multilabel-classification

This project is based on the Kaggle Competition named "Understanding the Amazon from space".
The project has about 40,000 images of the land imagery of the Amazon River Basin.
There are 17 different labels which have been used to classify the images using multilabel classification.
These labels are:
  1. Primary
  2. Agriculture
  3. Clear
  4. Road
  5. Haze
  6. Water
  7. Habitation
  8. Cultivation
  9. Cloudy
  10. Slash and burn
  11. Partly cloudy
  12. Conventional mine
  13. Bare ground
  14. Artisanal mine
  15. Selective logging
  16. Blow down
  17. Blooming

The project uses the popular VGGNet which was developed by VGG(Visual Geometry Group) from University of Oxford.
For Transfer Learning, the VGG-19 is used as the base model and 2 more layers are added to it.
A Flatten layer is also added at the end to bring all the activations to a single dimension and a Dense layer which consists of 17 blocks which is the number of labels to be predicted.
