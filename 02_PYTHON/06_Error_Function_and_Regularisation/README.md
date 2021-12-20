Markup :  # Calculating Error Function #


Markup :  We have a dataset of 40 training examples. 
Markup :  The i-th training example is denoted as (xi, ti), where xi is the example input and ti is the target output.
Markup :  The target inputs xi can be downloaded from training_inputs1.txt. 
Markup :  Each xi is a three-dimensional vector denoted as (xi, 1, xi, 2, xi, 3). 
Markup :  In file training_inputs1.txt, the number at row i and column j is the value for xi, j.
Markup :  The target outputs ti can be downloaded from training_outputs1.txt. 
Markup :  Each ti is a real number. Row i of training_outputs1.txt contains the value for ti.

Markup :  Error Function formula
Markup : ![ErrorFunction](https://github.com/milaan9/Machine_Learning_Algorithms_from_Scratch/blob/master/02_Python/Error_Function_and_Regularisation/img/errorfunction.png)

Markup :  Let w be a three dimensional vector (w1, w2, w3).
Markup :  Define y(xi, w) as follows: y(xi, w) = w1 * xi, 1 + w2 * xi, 2 + w3 * xi, 3.
Markup :  Part a: If w = (3, -1.5, -2), evaluate E(w) 
Markup :  Part b: If w = (5.2, -2, 1), evaluate E(w) 

Markup :  Regularisation formula
Markup : ![Regularisation](https://github.com/milaan9/Machine_Learning_Algorithms_from_Scratch/blob/master/02_Python/Error_Function_and_Regularisation/img/regularisederror.png)

Markup :  Part c: If w = (3, -1.5, -2) and ? = 0.25, evaluate the alternative error  
Markup :  Part d: If w = (5.2, -2, 1) and ? = 0.25, evaluate the alternative error  