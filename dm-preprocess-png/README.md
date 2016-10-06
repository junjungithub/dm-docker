# dm-preprocess-png
## Overview
Resizes all the training images to the same size and saves them to PNG format using ImageMagick. In addition, a label file at the image level is generated using information from the exams metadata table (see `generate_labels.py`).

## Output
- /preprocessedData/images/*.png
- /preprocessedData/metadata/image_labels.txt

## Contacts
Thomas Schaffter (thomas.schaffter@gmail.com)