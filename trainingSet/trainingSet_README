gloveTrack takes an input image (like a camera image) and 'normalizes' it by classifying each of the pixels (either one of the N glove colors, or background).

It achieves this step using a "supervised" machine learning algorithm called Expectation Maximization ("EM"). This algorithm is used to populate a statistical model known as a Guassian Mixture Model ("GMM") which can be used to classify the color of a given pixels.

Expectation Maximization is called a supervised algorithm because it needs a training set of labelled images to teach it the correspondance between an input pixel, and the classified pixel.

gloveTrack trains its statistical model by incrementally reading each file named "trainX_unlabelled.png" and "trainX_labelled.png" from X=0, 1, 2 and so on, until the file it attempts to read is unavailable.
