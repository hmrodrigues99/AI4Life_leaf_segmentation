Tried to use deep learning (transfer learning approach) for plant/leaf segmentation - https://github.com/ai4life-opencalls/oc-1-project-74/tree/main

Model failed segmentation for PSI RGB Rice plants (no masks generated).

Changes to original notebook include:
1) different numpy version install - 1.26.6 (1.24.4 fails due to python colab env using python 3.12)
2) warning message during segmentation to feedback if plant mask generation fails (no objects to attribute labels found)
