# Pyimagesearch-Crash-Course

This is everything I did during my Pyimagesearch Crash Course.

# Course

## Day 1: Face detection with OpenCV and Deep Learning

**Commands used:**

* **Face detection with Images:**

    > *python detect_faces.py --image rooster.jpg --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel*

    > *python detect_faces.py --image iron_chic.jpg --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel*

* **Face detection with Webcam:**

    > *python detect_faces_video.py --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel*

## Day 2: OpenCV Tutorial: A Guide to Learn OpenCV

**Commands used:**

* **OpenCV tutorial:**

> *python opencv_tutorial_01.py*

* **Counting objects:**

> *python opencv_tutorial_02.py --image images/tetris_blocks.png*

**Note:** To get the simple neural network working, create a folder structure called **/kaggle_dogs_vs_cats/train**, download the training dataset [Kaggle-Dogs vs. Cats](https://www.kaggle.com/c/dogs-vs-cats/data) and put the images into the **train** folder (that folder had too many images to upload to GitHub).

**Note:** For the search bing api, create a dataset directory first using the **mkdir dataset** command so that all imnages downloaded with be stored there. After that, execute **mkdir dataset/"class_to_search"** to make a subdirectory and run the search for whatever class your searching for.
