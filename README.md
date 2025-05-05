# machine-learning-exercise-3--neural-networks-and-classification-solved
**TO GET THIS SOLUTION VISIT:** [Machine Learning Exercise 3- Neural Networks and Classification Solved](https://www.ankitcodinghub.com/product/machine-learning-exercise-3-neural-networks-and-classification-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94647&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Machine Learning Exercise 3- Neural Networks and Classification Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
3: Multi-class Classification and Neural Networks

Machine Learning

Introduction

In this exercise, you will implement one-vs-all logistic regression and neural networks to recognize hand-written digits. Before starting the programming exercise, we strongly recommend watching the video lectures and completing the review questions for the associated topics.

To get started with the exercise, you will need to download the starter code and unzip its contents to the directory where you wish to complete the exercise. If needed, use the cd command in Octave/MATLAB to change to this directory before starting this exercise.

You can also find instructions for installing Octave/MATLAB in the “En- vironment Setup Instructions” of the course website.

Files included in this exercise

ex3.m – Octave/MATLAB script that steps you through part 1

ex3 nn.m – Octave/MATLAB script that steps you through part 2 ex3data1.mat – Training set of hand-written digits

ex3weights.mat – Initial weights for the neural network exercise submit.m – Submission script that sends your solutions to our servers displayData.m – Function to help visualize the dataset

fmincg.m – Function minimization routine (similar to fminunc) sigmoid.m – Sigmoid function

[⋆] lrCostFunction.m – Logistic regression cost function

[⋆] oneVsAll.m – Train a one-vs-all multi-class classifier

[⋆] predictOneVsAll.m – Predict using a one-vs-all multi-class classifier [⋆] predict.m – Neural network prediction function

⋆ indicates files you will need to complete 1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Throughout the exercise, you will be using the scripts ex3.m and ex3 nn.m. These scripts set up the dataset for the problems and make calls to functions that you will write. You do not need to modify these scripts. You are only required to modify functions in other files, by following the instructions in this assignment.

Where to get help

The exercises in this course use Octave1 or MATLAB, a high-level program- ming language well-suited for numerical computations. If you do not have Octave or MATLAB installed, please refer to the installation instructions in the “Environment Setup Instructions” of the course website.

At the Octave/MATLAB command line, typing help followed by a func- tion name displays documentation for a built-in function. For example, help plot will bring up help information for plotting. Further documentation for Octave functions can be found at the Octave documentation pages. MAT- LAB documentation can be found at the MATLAB documentation pages.

We also strongly encourage using the online Discussions to discuss ex- ercises with other students. However, do not look at any source code written by others or share your source code with others.

1 Multi-class Classification

For this exercise, you will use logistic regression and neural networks to recognize handwritten digits (from 0 to 9). Automated handwritten digit recognition is widely used today – from recognizing zip codes (postal codes) on mail envelopes to recognizing amounts written on bank checks. This exercise will show you how the methods you’ve learned can be used for this classification task.

In the first part of the exercise, you will extend your previous implemen- tion of logistic regression and apply it to one-vs-all classification.

1Octave is a free alternative to MATLAB. For the programming exercises, you are free to use either Octave or MATLAB.

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
1.1 Dataset

You are given a data set in ex3data1.mat that contains 5000 training exam- ples of handwritten digits.2 The .mat format means that that the data has been saved in a native Octave/MATLAB matrix format, instead of a text (ASCII) format like a csv-file. These matrices can be read directly into your program by using the load command. After loading, matrices of the correct dimensions and values will appear in your program’s memory. The matrix will already be named, so you do not need to assign names to them.

<pre>% Load saved matrices from file
</pre>
<pre>load('ex3data1.mat');
% The matrices X and y will now be in your Octave environment
</pre>
There are 5000 training examples in ex3data1.mat, where each training example is a 20 pixel by 20 pixel grayscale image of the digit. Each pixel is represented by a floating point number indicating the grayscale intensity at that location. The 20 by 20 grid of pixels is “unrolled” into a 400-dimensional vector. Each of these training examples becomes a single row in our data matrix X. This gives us a 5000 by 400 matrix X where every row is a training example for a handwritten digit image.

 —(x(1))T —   —(x(2))T — 

X =  .  .

— (x(m))T —

The second part of the training set is a 5000-dimensional vector y that contains labels for the training set. To make things more compatible with Octave/MATLAB indexing, where there is no zero index, we have mapped the digit zero to the value ten. Therefore, a “0” digit is labeled as “10”, while the digits “1” to “9” are labeled as “1” to “9” in their natural order.

1.2 Visualizing the data

You will begin by visualizing a subset of the training set. In Part 1 of ex3.m, the code randomly selects selects 100 rows from X and passes those rows to the displayData function. This function maps each row to a 20 pixel by 20 pixel grayscale image and displays the images together. We have provided

2This is a subset of the MNIST handwritten digit dataset (http://yann.lecun.com/ exdb/mnist/).

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
the displayData function, and you are encouraged to examine the code to see how it works. After you run this step, you should see an image like Figure 1.

Figure 1: Examples from the dataset

1.3 Vectorizing Logistic Regression

You will be using multiple one-vs-all logistic regression models to build a multi-class classifier. Since there are 10 classes, you will need to train 10 separate logistic regression classifiers. To make this training efficient, it is important to ensure that your code is well vectorized. In this section, you will implement a vectorized version of logistic regression that does not employ any for loops. You can use your code in the last exercise as a starting point for this exercise.

1.3.1 Vectorizing the cost function

We will begin by writing a vectorized version of the cost function. Recall that in (unregularized) logistic regression, the cost function is

1 􏰉m m i=1

To compute each element in the summation, we have to compute hθ(x(i)) for every example i, where h (x(i)) = g(θT x(i)) and g(z) = 1 is the

</div>
</div>
<div class="layoutArea">
<div class="column">
J(θ) =

</div>
<div class="column">
􏰂−y(i) log(hθ(x(i))) − (1 − y(i)) log(1 − hθ(x(i)))􏰃 .

</div>
</div>
<div class="layoutArea">
<div class="column">
θ

</div>
<div class="column">
1+e−z

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
sigmoid function. It turns out that we can compute this quickly for all our examples by using matrix multiplication. Let us define X and θ as

 — (x(1))T —   θ0 

 — (x(2))T —   θ1  X= .  and θ= . .

.. —(x(m))T — θn

Then, by computing the matrix product Xθ, we have

 —(x(1))Tθ—   —θT(x(1))— 

 —(x(2))Tθ—   —θT(x(2))—  Xθ =  .  =  . .

.. — (x(m))T θ — — θT (x(m)) —

In the last equality, we used the fact that aT b = bT a if a and b are vectors. This allows us to compute the products θT x(i) for all our examples i in one line of code.

Your job is to write the unregularized cost function in the file lrCostFunction.m Your implementation should use the strategy we presented above to calcu-

late θTx(i). You should also use a vectorized approach for the rest of the

cost function. A fully vectorized version of lrCostFunction.m should not contain any loops.

(Hint: You might want to use the element-wise multiplication operation (.*) and the sum operation sum when writing this function)

1.3.2 Vectorizing the gradient

Recall that the gradient of the (unregularized) logistic regression cost is a vector where the jth element is defined as

∂J = 1 􏰉m 􏰄(hθ(x(i)) − y(i))x(i)􏰅 . ∂θjm j

i=1

To vectorize this operation over the dataset, we start by writing out all

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
the partial derivatives explicitly for all θj,

</div>
</div>
<div class="layoutArea">
<div class="column">
where

</div>
<div class="column">
 

</div>
<div class="column">
hθ(x(1)) − y(1) hθ(x(2)) − y(2)

</div>
<div class="column">
 

</div>
</div>
<div class="layoutArea">
<div class="column">
∂J ∂θ0

∂J

∂θ1 

</div>
<div class="column">
􏰈m􏰄(i) (i)(i)􏰅 i=1 (hθ(x ) − y )x0

</div>
</div>
<div class="layoutArea">
<div class="column">
=

</div>
</div>
<div class="layoutArea">
<div class="column">
hθ (x) − y = 

</div>
</div>
<div class="layoutArea">
<div class="column">
 􏰈m􏰄 (i) (i)(i)􏰅

</div>
</div>
<div class="layoutArea">
<div class="column">
 i=1 (hθ(x )−y )x1  (h(x)−y)x

</div>
</div>
<div class="layoutArea">
<div class="column">
∂J1 􏰄 􏰅

</div>
</div>
<div class="layoutArea">
<div class="column">
 = 􏰈m (i) (i) (i) 

</div>
</div>
<div class="layoutArea">
<div class="column">
∂θ2   . 



∂J ∂θn

</div>
<div class="column">
m i=1 θ 2   . 

</div>
</div>
<div class="layoutArea">
<div class="column">
 . 

</div>
</div>
<div class="layoutArea">
<div class="column">
 􏰈m 􏰄(h (x(i)) − y(i))x(i)􏰅 i=1θ n

</div>
<div class="column">


</div>
</div>
<div class="layoutArea">
<div class="column">
1 􏰉m m i=1

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰀(hθ(x(i)) − y(i))x(i)􏰁 = m1 XT (hθ(x) − y).

</div>
</div>
<div class="layoutArea">
<div class="column">
 . .

</div>
</div>
<div class="layoutArea">
<div class="column">
. hθ(x(1)) − y(m)

</div>
</div>
<div class="layoutArea">
<div class="column">
Note that x(i) is a vector, while (hθ(x(i))−y(i)) is a scalar (single number). To understand the last step of the derivation, let βi = (hθ(x(i)) − y(i)) and observe that:

  β1

|| |β2

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰉

βix=x x …x .=Xβ,

</div>
</div>
<div class="layoutArea">
<div class="column">
(i) i|||.

</div>
</div>
<div class="layoutArea">
<div class="column">
(1)

</div>
<div class="column">
(2) (m) T βm

</div>
</div>
<div class="layoutArea">
<div class="column">
where the values βi = (hθ(x(i)) − y(i)).

The expression above allows us to compute all the partial derivatives without any loops. If you are comfortable with linear algebra, we encourage you to work through the matrix multiplications above to convince yourself that the vectorized version does the same computations. You should now implement Equation 1 to compute the correct vectorized gradient. Once you are done, complete the function lrCostFunction.m by implementing the gradient.

</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
<div class="layoutArea">
<div class="column">
(1)

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="section">
<div class="layoutArea">
<div class="column">
Debugging Tip: Vectorizing code can sometimes be tricky. One com- mon strategy for debugging is to print out the sizes of the matrices you are working with using the size function. For example, given a data ma- trix X of size 100 × 20 (100 examples, 20 features) and θ, a vector with dimensions 20×1, you can observe that Xθ is a valid multiplication oper- ation, while θX is not. Furthermore, if you have a non-vectorized version of your code, you can compare the output of your vectorized code and non-vectorized code to make sure that they produce the same outputs.

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
1.3.3 Vectorizing regularized logistic regression

After you have implemented vectorization for logistic regression, you will now add regularization to the cost function. Recall that for regularized logistic regression, the cost function is defined as

</div>
</div>
<div class="layoutArea">
<div class="column">
J(θ) =

</div>
<div class="column">
1 􏰉m m i=1

</div>
<div class="column">
􏰂−y(i) log(hθ(x(i))) − (1 − y(i)) log(1 − hθ(x(i)))􏰃 +

</div>
<div class="column">
λ 􏰉n 2m j=1

</div>
<div class="column">
θj2.

</div>
</div>
<div class="layoutArea">
<div class="column">
Note that you should not be regularizing θ0 which is used for the bias term.

Correspondingly, the partial derivative of regularized logistic regression cost for θj is defined as

for j = 0

Once again, you should not put any loops into your code.

</div>
</div>
<div class="layoutArea">
<div class="column">
∂J(θ) 1􏰉m

= (hθ(x(i)) − y(i))x(i)

</div>
</div>
<div class="layoutArea">
<div class="column">
∂θ0m j i=1

</div>
</div>
<div class="layoutArea">
<div class="column">
∂ J ( θ ) 􏰆 1 􏰉m 􏰇 λ = (hθ(x(i)) − y(i))x(i) + θj

</div>
</div>
<div class="layoutArea">
<div class="column">
for j ≥ 1

Now modify your code in lrCostFunction to account for regularization.

</div>
</div>
<div class="layoutArea">
<div class="column">
∂θjm jm i=1

</div>
</div>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="section">
<div class="layoutArea">
<div class="column">
Octave/MATLAB Tip: When implementing the vectorization for reg- ularized logistic regression, you might often want to only sum and update certain elements of θ. In Octave/MATLAB, you can index into the matri- ces to access and update only certain elements. For example, A(:, 3:5) = B(:, 1:3) will replaces the columns 3 to 5 of A with the columns 1 to 3 from B. One special keyword you can use in indexing is the end keyword in indexing. This allows us to select columns (or rows) until the end of the matrix. For example, A(:, 2:end) will only return elements from the 2nd to last column of A. Thus, you could use this together with the sum and .^ operations to compute the sum of only the elements you are interested in (e.g., sum(z(2:end).^2)). In the starter code, lrCostFunction.m, we have also provided hints on yet another possible method computing the regularized gradient.

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
You should now submit your solutions.

1.4 One-vs-all Classification

In this part of the exercise, you will implement one-vs-all classification by training multiple regularized logistic regression classifiers, one for each of the K classes in our dataset (Figure 1). In the handwritten digits dataset, K = 10, but your code should work for any value of K.

You should now complete the code in oneVsAll.m to train one classifier for each class. In particular, your code should return all the classifier parameters in a matrix Θ ∈ RK×(N+1) , where each row of Θ corresponds to the learned logistic regression parameters for one class. You can do this with a “for”-loop from 1 to K, training each classifier independently.

Note that the y argument to this function is a vector of labels from 1 to 10, where we have mapped the digit “0” to the label 10 (to avoid confusions with indexing).

When training the classifier for class k ∈ {1,…,K}, you will want a m- dimensional vector of labels y, where yj ∈ 0,1 indicates whether the j-th training instance belongs to class k (yj = 1), or if it belongs to a different class (yj = 0). You may find logical arrays helpful for this task.

</div>
</div>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="section">
<div class="layoutArea">
<div class="column">
Octave/MATLAB Tip: Logical arrays in Octave/MATLAB are arrays which contain binary (0 or 1) elements. In Octave/MATLAB, evaluating the expression a == b for a vector a (of size m×1) and scalar b will return a vector of the same size as a with ones at positions where the elements of a are equal to b and zeroes where they are different. To see how this works for yourself, try the following code in Octave/MATLAB:

<pre>   a = 1:10; % Create a and b
   b = 3;
   a == b    % You should try different values of b here
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Furthermore, you will be using fmincg for this exercise (instead of fminunc). fmincg works similarly to fminunc, but is more more efficient for dealing with

a large number of parameters.

After you have correctly completed the code for oneVsAll.m, the script ex3.m will continue to use your oneVsAll function to train a multi-class clas- sifier.

You should now submit your solutions.

1.4.1 One-vs-all Prediction

After training your one-vs-all classifier, you can now use it to predict the digit contained in a given image. For each input, you should compute the “probability” that it belongs to each class using the trained logistic regression classifiers. Your one-vs-all prediction function will pick the class for which the corresponding logistic regression classifier outputs the highest probability and return the class label (1, 2,…, or K) as the prediction for the input example.

You should now complete the code in predictOneVsAll.m to use the one-vs-all classifier to make predictions.

Once you are done, ex3.m will call your predictOneVsAll function using the learned value of Θ. You should see that the training set accuracy is about 94.9% (i.e., it classifies 94.9% of the examples in the training set correctly).

You should now submit your solutions.

</div>
</div>
<div class="layoutArea">
<div class="column">
9

</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="layoutArea">
<div class="column">
2 Neural Networks

In the previous part of this exercise, you implemented multi-class logistic re- gression to recognize handwritten digits. However, logistic regression cannot form more complex hypotheses as it is only a linear classifier.3

In this part of the exercise, you will implement a neural network to rec- ognize handwritten digits using the same training set as before. The neural network will be able to represent complex models that form non-linear hy- potheses. For this week, you will be using parameters from a neural network that we have already trained. Your goal is to implement the feedforward propagation algorithm to use our weights for prediction. In next week’s ex- ercise, you will write the backpropagation algorithm for learning the neural network parameters.

The provided script, ex3 nn.m, will help you step through this exercise. 2.1 Model representation

Our neural network is shown in Figure 2. It has 3 layers – an input layer, a hidden layer and an output layer. Recall that our inputs are pixel values of digit images. Since the images are of size 20×20, this gives us 400 input layer units (excluding the extra bias unit which always outputs +1). As before, the training data will be loaded into the variables X and y.

You have been provided with a set of network parameters (Θ(1),Θ(2)) already trained by us. These are stored in ex3weights.mat and will be loaded by ex3 nn.m into Theta1 and Theta2 The parameters have dimensions that are sized for a neural network with 25 units in the second layer and 10 output units (corresponding to the 10 digit classes).

<pre>% Load saved matrices from file
</pre>
<pre>load('ex3weights.mat');
</pre>
<pre>% The matrices Theta1 and Theta2 will now be in your Octave
% environment
% Theta1 has size 25 x 401
% Theta2 has size 10 x 26
</pre>
3You could add more features (such as polynomial features) to logistic regression, but that can be very expensive to train.

</div>
</div>
<div class="layoutArea">
<div class="column">
10

</div>
</div>
</div>
<div class="page" title="Page 11">
<div class="layoutArea">
<div class="column">
Figure 2: Neural network model.

2.2 Feedforward Propagation and Prediction

Now you will implement feedforward propagation for the neural network. You will need to complete the code in predict.m to return the neural network’s prediction.

You should implement the feedforward computation that computes hθ(x(i)) for every example i and returns the associated predictions. Similar to the one-vs-all classification strategy, the prediction from the neural network will be the label that has the largest output (hθ(x))k.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Implementation Note: The matrix X contains the examples in rows. When you complete the code in predict.m, you will need to add the column of 1’s to the matrix. The matrices Theta1 and Theta2 contain the parameters for each unit in rows. Specifically, the first row of Theta1 corresponds to the first hidden unit in the second layer. In Octave/MAT- LAB, when you compute z(2) = Θ(1)a(1), be sure that you index (and if necessary, transpose) X correctly so that you get a(l) as a column vector.

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Once you are done, ex3 nn.m will call your predict function using the loaded set of parameters for Theta1 and Theta2. You should see that the

</div>
</div>
<div class="layoutArea">
<div class="column">
11

</div>
</div>
</div>
<div class="page" title="Page 12">
<div class="layoutArea">
<div class="column">
accuracy is about 97.5%. After that, an interactive sequence will launch dis- playing images from the training set one at a time, while the console prints out the predicted label for the displayed image. To stop the image sequence, press Ctrl-C.

You should now submit your solutions.

</div>
</div>
</div>
