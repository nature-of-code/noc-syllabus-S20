# Machine Learning and Neural Networks

## ml5.js
* [ml5 Coding Train video playlist](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6YPSwT06y_AEYTqIwbeam3y)
* [ml5 website](https://ml5js.org/), [ml5 github](https://github.com/ml5js)
* [Image Classification Transfer Learning example code](https://editor.p5js.org/ml5/sketches/BkEeFyBhm)
* [Image "Regression" Transfer Learning example code](https://editor.p5js.org/ml5/sketches/B1Gntkrhm)

## TensorFlow.js
* [Intro to TensorFlow.js video playlist](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6YIeVA3dNxbR9PYj4wV31oQ)
* [Building a "Color Classifier" with TensorFlow.js video playlist](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6bmMRCIoTi72aNWHo7epX4L)
* [Yining Shi](https://github.com/yining1023/)'s [TensorFlow.js Doodle Classifier](https://github.com/yining1023/machine-learning-for-the-web/tree/master/week3-1-doodleclassifier)
* [TensorFlow.js website](https://www.tensorflow.org/js/)
* [Coding Challenge: Solving XOR with tf.js](https://thecodingtrain.com/CodingChallenges/106-xor-tfjs.html)
* [Coding Challenge: Linear Regression with tf.js](https://thecodingtrain.com/CodingChallenges/104-linear-regression-tfjs.html)
* [Coding Challenge: Polynomial Regression with tf.js](https://thecodingtrain.com/CodingChallenges/105-polynomial-regression-tfjs.html)

## Building a Neural Network from Scratch
* [Neural Networks (Nature of Code Chapter 10)](http://natureofcode.com/book/chapter-10-neural-networks/)
* [Perceptron Video](https://youtu.be/ntKn5TPHHAk), [Perceptron p5.js code](https://editor.p5js.org/natureofcode/sketches/HkJ0cRmux)
* [3Blue1Brown Neural Network series](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)
* [Toy Neural Network JavaScript library](https://github.com/CodingTrain/Toy-Neural-Network-JS)
* [Coding Train Neural Network Playlist](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6aCibgK1PTWWu9by6XFdCfh)
* [Coding Train Doodle Classifier Playlist](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6Zs14zKVuTuit6jApJgoYZQ)

## Machine Learning Background and History

### What is a "Machine Learning"? (From [Andrew Ng's Coursera Course](https://www.coursera.org/learn/machine-learning))
* "Field of study that gives computers the ability to learn without being explicitly programmed." -- Arthur Samuels (1959). [Self-learning and checkers](https://en.wikipedia.org/wiki/Arthur_Samuel#Computer_checkers_.28draughts.29_development).
* "A computer program is said to learn from experience E with respect to some class of tasks T and performance measure P, if its performance at tasks in T, as measured by P, improves with experience E." -- Tom Mitchell (1998): [Maching Learning book](http://amzn.to/2nLdRgQ).
  * Example: classifying images of dogs and cats.
    * E = Watching you classify images as dogs or cats.
    * T = Classifying images as dogs or cats.
    * P = The % of images correctly classified.

### Supervised Learning
> In supervised learning, we are given a data set and already know what our correct output should look like, having the idea that there is a relationship between the input and the output. -- Andrew Ng
> Supervised Learning is a strategy that involves a "teacher" that trains the learning system. For example, consider facial recognition. The "teacher" shows the network a bunch of faces (the teacher already knows the names associated with each face). The learning system makes its guesses and the teacher provides the answers. The learning system can then compare its answers to the known “correct” ones and make adjustments according to its errors. -- [Nature of Code Chapter 10](http://natureofcode.com/book/chapter-10-neural-networks/):

### Classification and Regression
* Classification and regression both involve making a "prediction" based on input data.
* Classification refers to predicting an output with a discrete set of possibilities like a set of categories or labels. For example: "Given an input image, is it a dog or cat?"
* Regression refers to predicting an "continuous" output (a fancy way of saying number). For example: "Given the number of bedrooms, what is the price of a house?" or "Given an input image of a cat, how much does the cat weigh?"

### History
This short list thanks to Andrey Kurenkov's excellent ['Brief' History of Neural Nets and Deep Learning](http://www.andreykurenkov.com/writing/a-brief-history-of-neural-nets-and-deep-learning/)
* In 1943, Warren S. McCulloch, a neuroscientist, and Walter Pitts, a logician, developed the first conceptual model of an artificial neural network. In their paper, "[A logical calculus of the ideas immanent in nervous activity](https://pdfs.semanticscholar.org/5272/8a99829792c3272043842455f3a110e841b1.pdf),” they describe the concept of a neuron, a single cell living in a network of cells that receives inputs, processes those inputs, and generates an output.
* Hebb's Rule from [The Organization of Behavior: A Neuropsychological Theory](https://alexa.design/2nyUyJi): "When an axon of cell A is near enough to excite a cell B and repeatedly or persistently takes part in firing it, some growth process or metabolic change takes place in one or both cells such that A's efficiency, as one of the cells firing B, is increased."
* Invented in 1957 by Frank Rosenblatt at the Cornell Aeronautical Laboratory ([original paper](http://www.ling.upenn.edu/courses/cogs501/Rosenblatt1958.pdf)), a perceptron is the simplest neural network possible: a computational model of a single neuron. A perceptron consists of one or more inputs, a processor, and a single output.
* In 1969, in their book [Perceptrons](https://mitpress.mit.edu/books/perceptrons) Marvin Minksy and Seymour Papert demonstrate the limitations of perceptrons to solve only "linearly separable" problems.  AI Winter #1!
* Paul Werbos's 1974 thesis [Beyond Regression: New Tools for Prediction and Analysis in the Behavioral Sciences](https://books.google.com/books/about/Beyond_Regression.html?id=z81XmgEACAAJ) proposes "backpropagation" as a solution to adjusting weights in the hidden layers of a neural network. The technique was popularized in the 1986 paper [Learning representations by back-propagating errors](http://www.iro.umontreal.ca/~vincentp/ift3395/lectures/backprop_old.pdf) by David Rumelhart, Geoffrey Hinton, and Ronald Williams
* Neural Networks come back with Yann LeCunn's paper [Backpropagation Applied to Handwritten Zip Code Recognition](http://yann.lecun.com/exdb/publis/pdf/lecun-89e.pdf). Here's a [1993 video on convolutional neural networks](https://youtu.be/FwFduRA_L6Q). But AI Winter returns again with the "[vanishing gradient problem](https://en.wikipedia.org/wiki/Vanishing_gradient_problem)."
* "Deep Learning" thaws the wintr with new methodologies for training: [A fast learning algorithm for deep belief nets ](https://www.cs.toronto.edu/~hinton/absps/fastnc.pdf) by Hinton, Osindero, Teh and raw power with GPUs: [Large-scale Deep Unsupervised Learning using Graphics Processors](http://www.machinelearning.org/archive/icml2009/papers/218.pdf)

## Additional Reading
* [A Quick Introduction to Neural Networks](https://ujjwalkarn.me/2016/08/09/quick-intro-neural-networks/) by Ujjwal Karn
* [Let’s code a Neural Network from scratch](https://medium.com/typeme/lets-code-a-neural-network-from-scratch-part-1-24f0a30d7d62) by Charles Fried
* [Linear Algebra Cheatsheet](https://medium.com/towards-data-science/linear-algebra-cheat-sheet-for-deep-learning-cd67aba4526c) by Brendan Fortuner
* [A 'Brief' History of Neural Nets and Deep Learning](http://www.andreykurenkov.com/writing/a-brief-history-of-neural-nets-and-deep-learning/) by Andrey Kurenkov
* [Make Your Own Neural Network](http://amzn.to/2pgOaT9) by Tariq Rashid
* [Chapter 22 of The Computational Beauty of Nature](http://amzn.to/2oUYCjT) by Gary Flake

## Additional Processing examples
* [Nature of Code Chapter 10 Processing examples](https://github.com/shiffman/The-Nature-of-Code-Examples/tree/master/chp10_nn)
* [Charles Fried's Neural Network in Processing](https://github.com/CharlesFr/ANN_Tutorial)
* [Another Processing Example](https://github.com/ANyanCatFan/SimpleNN)

## Python examples
* [Make Your Own Neural Network ](https://github.com/makeyourownneuralnetwork/makeyourownneuralnetwork/) from Tariq Rashid
* [Abishek's Tensorflow Example](https://github.com/shekit/machine-learning-demystified/blob/master/week2/NeuralNet.ipynb)

## Homework
* TBD
