# parallel_algorithms
A parallel algorithm to predict the outcomes using k nearest neighbours
Running time Complexity

In this project, we have used two functions, knn_predict and distance. knn_predict calculates distance between all the train and test points, since knn_predict iterates through both test and train data points, its running time complexity will be in the range of O(n^2)

Function distance(), will measure the euclidean distance between a corresponding test point and all other train data points. Since we are only iterating one data set, running time complexity will be in the order of O(n).

In conclusion, knn_predict() will have a polynomial growth and distance() will have a linear growth
