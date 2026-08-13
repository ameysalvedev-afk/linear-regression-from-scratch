# linear-regression-from-scratch
My first ML model built from scratch using numpy, no sklearn

This project implements linear regression using only NumPy — no scikit-learn or pre-built ML libraries. I built it to properly understand how a model actually learns, instead of just calling .fit() on a library function.

The model predicts [y] from [x] using gradient descent to minimize Mean Squared Error. On each iteration, it computes how wrong the current prediction is, calculates the gradient (direction to adjust the weights), and updates the weight (w) and bias (b) to reduce error over time.

What I learned: Building this made gradient descent click for me — it's not magic, it's just repeatedly asking "which direction reduces my error, and by how much" and taking small steps that way. It also helped me connect the linear algebra concepts (vectors, matrix operations) I was learning separately to something concrete and working.
