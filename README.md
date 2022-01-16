# PatchCamelyonModel
For this project, I used the PatchCamelyon dataset on TensorFlow. I used InceptionV3 as my base and added dense, batch normalization, and dense layers to complete my model. This model identifies metastasis in patches of cancer cell slides with an approximate accuracy of 80%.

I wrote the code originally on Google Colab. I imported the dataset directly from TensorFlow.

More information on the dataset used can be found here: https://www.tensorflow.org/datasets/catalog/patch_camelyon. During my project, I compared my accuracy and use of optimizers with that of Geert Lidjens, whose introductory guide for coding a model with this dataset can be found here: https://geertlitjens.nl/post/getting-started-with-camelyon/. Lastly, some of the adjustments in the parameters of the model, such as dropout and learning rates, were inspired by the parameters used in the research by Yun Lui et al. on "Detecting Cancer Metastases on Gigapixel Pathology Images" using the Camelyon16 dataset. The link to their paper can be found here: https://arxiv.org/pdf/1703.02442.pdf.
