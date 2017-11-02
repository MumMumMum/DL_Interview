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
          Optimizer: SGD,GD, Adam optimizer,ADAGRAD(has momentum and learning rate decay)  
          Fetaures =(28 * 28 * 3) and Labels(1,2,3).   
          Onehttps://carnd.slack.com/team/U3M2HDNBY hot encoding is not good if labels are like in large nos  
          Cross Entropy is used to compare value of One hot encoding and prob. It is measure of how good is our prediction  
          We reduce cross entropy loss and its gradient to cal new wt.  
          Learning rate decay and momentun also HP which I have not used  
 . Well conditioned ip is very imp for GD. menaing data should ve 0 mean and sigma should be equl.  
 . Take weights from normal Gaussian distribution  
 .Pixel value should be 128-x/128 normalized  
 .GD does not convereg if loss is too big are too small, to get loss in range of values we do pre procssing of x an d wt  
 .RELU: Rectified linaer Units, non linerality   
 .Neural Networks, Logistic regressionis is linear nw. To get non linear model we use Neural nets. 
    Linear model cascade with non     linear model to make a stable non linear model to get more comples jobs done. Relus are hideen layers and non linear models
 . Back prop, computes derivate and thus gradient for each of wt in model   
 .Model save restore fine tune   
 .Add more layers for better models.  
 .Regularization:are measures taken to avoid over fitting.  
    1. Stop training once validation scores are good.  
    2. L2 regularizing add term L2 to loss which penalize the large wt.  
    3. Info flowing from 1 ly to other passes thru activation layer, here in drop out some % of info is drop to increase generalization   
    
    L1 regu is lasso 
    L2 regu is ridge 
    
     Statistical Invariance, helps in wt sharing and leads to convolution Networks
     Covnets share parameters across space not recurent networks RNN
     
     General Arch for convnets is convnet=pooling(max/avg)/convnet=pooling(max/avg)/fully connected layer/fully connected layer/ classifier
     
     Pooling layer: here we do con with small stride and combine parameters in neighborhood using max pooling or avg pooling. This reduce spatial info with parmeters loss and same depth.
    

