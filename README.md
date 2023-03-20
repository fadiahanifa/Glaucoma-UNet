# Glaucoma-UNet

Glaucoma is eye disease which is caused by increase of intraocular pressure. The pressure is damaging optic nerve head and could lead to partially or even entirely loss of eyesight if there is no appropriate treatment. In Indonesia, only 51.4% of glaucoma cases were only examined after they were at the severe stage of glaucoma namely when there is already significant damage to the eye or even when vision has been greatly reduced. Therefore, early glaucoma detection is crucial so that glaucoma can be treated as fast as possible. Currently, there are many developments in this field that have been carried out using various types of approaches. One of the approaches is by quantification of optic disc and cup’s such as cup to disc ratio. In this approach, we carried out the classification using a four step algorithm.

## Algorithm

0. Image Preprocessing and Data Loading
1. Disc Localization
2. Optic Disc and Optic Cup Segmentation using U-Net
3. Feature Extraction (CDR and RDR)
4. Glaucoma Classification

## Run Model
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github.com/fadiahanifa/Glaucoma-UNet/blob/main/Glaucoma%20Detection.ipynb))
