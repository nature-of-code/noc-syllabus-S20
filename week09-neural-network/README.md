# Machine Learning and Neural Networks

## Machine Learning Reading
* [A People’s Guide to AI](https://www.alliedmedia.org/files/peoples-guide-ai.pdf) by Mimi Onuoha and Mother Cyborg (Diana Nucera)
* [Data & Society’s Algorithmic Accountability: A Primer](https://datasociety.net/wp-content/uploads/2018/04/Data_Society_Algorithmic_Accountability_Primer_FINAL-4.pdf)

## Creative Machine Learning Helpful Videos
* Watch [Seeing Machines Think — Martin Wattenberg and Fernanda Viégas](https://youtu.be/ugkfmHBW74Q)
* Watch [Kyle McDonald - Weird Intelligence](https://vimeo.com/304110435)

## ml5.js
* [ml5 website](https://ml5js.org/), [ml5 github](https://github.com/ml5js)
* [Introduction to Machine Learning slides](https://docs.google.com/presentation/d/1C5V6YOs4hgWFeKKdpGwNjeRLuYOCwipLlSzKNOzsUnQ/edit). These slides are from @joeyklee's [friendly introduction to machine learning and ml5.js - workshop](https://github.com/ml5js/ml5-friendly-intro-to-ml-2019f#introduction-to-machine-learning) and also based off of @yining1023's [Machine Learning for the Web](https://github.com/yining1023/machine-learning-for-the-web)
* [Intro to ml5.js video tutorial](https://youtu.be/jmznx0Q1fP0?list=PLRqwX-V7Uu6YPSwT06y_AEYTqIwbeam3y)
* [Train Your Own Neural Network with ml5.js video tutorial](https://thecodingtrain.com/learning/ml5/6.1-train-your-own.html)
* [Teachable Machine with ml5.js](https://thecodingtrain.com/TeachableMachine/)


## What is a Neural Network?
* [Neural Networks (Nature of Code Chapter 10)](http://natureofcode.com/book/chapter-10-neural-networks/)
* [Perceptron Video](https://youtu.be/ntKn5TPHHAk), [Perceptron p5.js code](https://editor.p5js.org/natureofcode/sketches/HkJ0cRmux)
* [3Blue1Brown Neural Network series](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)

## Machine Learning Background and History

### What is a "Machine Learning"? (From [Andrew Ng's Coursera Course](https://www.coursera.org/learn/machine-learning))
* "Field of study that gives computers the ability to learn without being explicitly programmed." -- Arthur Samuels (1959). [Self-learning and checkers](https://en.wikipedia.org/wiki/Arthur_Samuel#Computer_checkers_.28draughts.29_development).
* "A computer program is said to learn from experience E with respect to some class of tasks T and performance measure P, if its performance at tasks in T, as measured by P, improves with experience E." -- Tom Mitchell (1998): [Machine Learning book](http://amzn.to/2nLdRgQ).
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
