# DL_Interview  
. SSE = sum of squared error  
. Precpeptron model= node edges activation function input weights    
. Gradient Descent ... As SSE is parabola, gradient descent is derivatie of err and minimizing it It is steepest path of descent   
. Stochastic Gradient Descent : Is for batch processing on data set and applying GD.    
     For SGD the variance over each batch decrease if batch size is large.   
     SO taking a batch size supported by GPU is advisabale.   
. Session is a process where inputs are apllied at graph nodes and sent to GPU for processing the inputs at ip knob
. Tensors are placeholders for variables and ip, generalized vectors or mattrix or vraiables 
. TF is computation involving tensors,flow of tensors in graph   
. Learning Rate is hyper parameter , it is a multiplier const applied to grad desc to get to min err  
    It is how weights are increased or decreased  
. Models:
    Linear Regression: for given x y is op, continous function, temp vs heat, price vs area
    Logistic regression: OP is discrete, T/F , Red/Green/Yellow. Resp is in categories or classes.
          Linear Logisctic classifier WX+B = Y 
          where Y is score. or Logits
          Softamx function converts scores to probablity
          One hot encoding makes prob 1 or 0 
          Optimizer: SGD,GD, Adam optimizer
          Fetaures =(28 * 28 * 3) and Labels(1,2,3).

