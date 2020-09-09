# Curve-fitting & regression from scratch

This is my short implementation of fitting a curve on some given data (real world or otherwise), without using libraries like scikit-learn.

Made in python using numpy and pandas.

## Formula:

<!-- Σ --->
<h3>y = a + bx + cx<sup>2</sup></h3>
<hr />

<h3>Σy = n * a + b Σx + c Σx<sup>2</sup></h3>
<h3>Σxy = a Σx + b Σx<sup>2</sup> + c Σx<sup>3</sup></h3>
<h3>Σx<sup>2</sup>y = a Σx<sup>2</sup> + b Σx<sup>3</sup> + c Σx<sup>4</sup></h3>

<hr >

## Note:
- The data is got from [kaggle](https://kaggle.com) from [this page](https://www.kaggle.com/andonians/random-linear-regression)
