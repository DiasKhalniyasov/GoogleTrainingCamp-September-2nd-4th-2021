# GoogleTrainingCamp-September-2nd-4th-2021
GoogleTrainingCamp in Sapienza University of Rome on building an image search engine

Main goal was to build an image search engine on COCO dataset in two steps:
1. Train a model for image captioning.
2. Build a similarity function for generated queries.

The baseline (InceptionV3 and Jaccard-Distance; score 0.06597) could be found here https://github.com/SapienzaTrainingCamp/GoogleTrainingCamp

In final submission, our team used pretrained InceptionV3 and pretrained Glove 6B with Cosine Similarity. (score 0.13732)

All code was executed on Colab, due to short time given on the task.
