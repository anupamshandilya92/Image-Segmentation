# Image-Segmentation
Image Segmentation techniques. Trained Mask RCNN on various publicly available data sets.

The data consists of following files:
  1. JPG files of images. (We will call them as jpg_img) These are pictures containing various object classes. For Pascal VOC dataset there are 20 classes.
  2. JPG files of masks. These contain masks for various objects in an image. There are multiple masks for one jpg_img, one for each object in the image.
  3. Annotation file - this is genreally an XML or JSON file. There is one file for each jpg_img file. It contains the coordinates of the bounding box for each object present and name of its class. Depending on the dataset it may also contain the coordinates of pixels of the mask in Run Length Encoded format.
  
  
