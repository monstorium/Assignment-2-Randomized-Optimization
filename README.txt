I used Weka 3.8.3 (the multilayer perceptron classifier) for my backprop on the Breast Cancer data set. I used a modified version of ABAGIL ofr everything else.

All my data sets and code can be found here:

https://github.com/monstorium/Assignment-2-Randomized-Optimization


You have to have Apache ant installed in your computer. Run Ant in the ABAGIL directory to make sure it works on your computer.

Neural Network Tests:
   -Randomized Hill Climbing:
   		java -cp ABAGAIL.jar tests.OptdigitsTest 3 5000 rhc

   		where 3 is the number of hidden layer nodes, and 5000 is the number of iterations

   -Simulated Annealing

   		java -cp ABAGAIL.jar tests.OptdigitsTest 3 5000 sa

   		where 3 is the number of hidden layer nodes, and 5000 is the number of iterations

   -Genetic Algorithm:
   		java -cp ABAGAIL.jar tests.OptdigitsTest 3 5000 ga

   		where 3 is the number of hidden layer nodes, and 5000 is the number of iterations


    If you want to modify the hyperparameters, you have to do that inside of OptdigitsTest.java. You should run these commands from project2/abagail/ABAGAIL.


Randomized Optimization Tests:
	-Traveling Salesman
		java -cp ABAGAIL.jar opt.test.MyTravelingSalesmanTest
	-N-Queens
		java -cp ABAGAIL.jar opt.test.MyNQueensTest
	-Knapsack
		java -cp ABAGAIL.jar opt.test.MyKnapsackTest


All commands will write to a csv file in the directory you're running it from.