# Matrix_Math_JS

Basic matrix functionality. Consists of a Matrix class. 


# small documentation.

Create a new matrix: 
  let m = new Matrix(y,x); 
  For a neural network weight matrix, y will stand for the amount of output nodes and x for the amount of input nodes
  X is optional, if x is not given as a parameter it will automatically become 1 and the matrix will be formed as an array. \
  
  let m = new Matrix(3, 2); //This can be an example for a weight matrix.
  let n = new Matrix(2); //This could then be the input layer.
  
  let o = Matrix.product(m,n); //This would then create the output layer with y = 3 and x = 1.
  
  
  
 
