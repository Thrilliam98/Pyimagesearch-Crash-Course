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

> *python opencv_tutorial_02.py --image tetris_blocks.png*

## Day 3: Document Scanner

**Commands used:**

> *python scan.py --image images/page.jpg*

## Day 4: Bubble sheet multiple choice scanner and test grader using OMR, Python, and OpenCV

**Commands used:**

> *python test_grader.py --image images/test_01.png*

## Day 5: Ball Tracking with OpenCV

**Commands used:**

* **Using Video:**

    > *python ball_tracking.py --video ball_tracking_example.mp4*

* **Using Webcam:**

    > *python ball_tracking.py (Note: To see any results, you will need a green object with the same HSV color range was used in the demo)*

## Day 6: Measuring size of objects in an image with OpenCV

**Commands used:**

> *python object_size.py --image images/example_01.png --width 0.955*

> *python object_size.py --image images/example_02.png --width 0.955*

> *python object_size.py --image images/example_03.png --width 3.5*

## Day 8: Facial landmarks with dlib, OpenCV and Python

**Commands used:**

> *python facial_landmarks.py --shape-predictor model/shape_predictor_68_face_landmarks.dat --image images/example_01.jpg*

> *python facial_landmarks.py --shape-predictor model/shape_predictor_68_face_landmarks.dat --image images/example_02.jpg*

> *python facial_landmarks.py --shape-predictor model/shape_predictor_68_face_landmarks.dat --image images/example_03.jpg*

## Day 9: Eye blink detection with OpenCV, Python and dlib

**Commands used:**

> *python detect_blinks.py --shape-predictor model/shape_predictor_68_face_landmarks.dat --video videos/blink_detection_demo.mp4*

## Day 10: Drowsiness detection with OpenCV

**Commands used:**

> *python detect_drowsiness.py --shape-predictor model/shape_predictor_68_face_landmarks.dat --alarm sounds/alarm.wav*

## Day 12: A simple neural network with Python and Keras

**Note:** To get the simple neural network working, create a folder structure called **/kaggle_dogs_vs_cats/train**, download the training dataset [Kaggle-Dogs vs. Cats](https://www.kaggle.com/c/dogs-vs-cats/data) and put the images into the **train** folder (that folder had too many images to upload to GitHub).

**Command used - Training:**

> *python simple_neural_network.py --dataset kaggle_dogs_vs_cats --model output/simple_neural_network.hdf5*

**Command used - Test:**

> *python test_network.py --model output/simple_neural_network.hdf5 --test-images test_images*

## Day 13: Deep learning with OpenCV

**Commands used:**

> *python deep_learning_with_opencv.py --image images/jemma.png --prototxt model/bvlc_googlenet.prototxt --model model/bvlc_googlenet.caffemodel --labels model/synset_words.txt*

> *python deep_learning_with_opencv.py --image images/traffic_light.png --prototxt model/bvlc_googlenet.prototxt --model model/bvlc_googlenet.caffemodel --labels model/synset_words.txt*

> *python deep_learning_with_opencv.py --image images/eagle.png --prototxt model/bvlc_googlenet.prototxt --model model/bvlc_googlenet.caffemodel --labels model/synset_words.txt*

> *python deep_learning_with_opencv.py --image images/vending_machine.png --prototxt model/bvlc_googlenet.prototxt --model model/bvlc_googlenet.caffemodel --labels model/synset_words.txt*

## Day 14: How to (quickly) build a deep learning image dataset

**Note:** For the search bing api, create a dataset directory first using the **mkdir dataset** command so that all imnages downloaded with be stored there. After that, execute **mkdir dataset/"class_to_search"** to make a subdirectory and run the search for whatever class you're searching for.

**Commands used:**

> *python search_bing_api.py --query "pokemon_class_to_search" --output dataset/pokemon_class_to_search*

## Day 15: Keras and Convolutional Neural Networks (CNNs)

**Command used - Training:**

> *python train.py --dataset dataset --model pokedex.model --labelbin lb.pickle*

**Command used - Testing:**

> *python classify.py --model pokedex.model --labelbin lb.pickle --image examples/charmander_counter.png*

> *python classify.py --model pokedex.model --labelbin lb.pickle --image examples/bulbasaur_plush.png*

> *python classify.py --model pokedex.model --labelbin lb.pickle --image examples/mewtwo_toy.png*

> *python classify.py --model pokedex.model --labelbin lb.pickle --image examples/pikachu_toy.png*

> *python classify.py --model pokedex.model --labelbin lb.pickle --image examples/squirtle_plush.png*

> *python classify.py --model pokedex.model --labelbin lb.pickle --image examples/charmander_hidden.png*

## Day 16: Real-time object detection with deep learning and OpenCV

**Commands used:**

> *python real_time_object_detection.py --prototxt model/MobileNetSSD_deploy.prototxt.txt --model model/MobileNetSSD_deploy.caffemodel*

---

**Credits to Adrian Rosebrock on <http://www.pyimagesearch.com>**
