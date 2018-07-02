# "Machine Learning" Notes: (notes from the course https://www.coursera.org/learn/machine-learning)   

# Introduction  
  ## 1. Supervised Learning  
      In supervised learning, we are given a data set and already know what our correct output should look like, having the idea that there is a relationship between the input and the output.
      
   ### 1.a Regression  
          In a regression problem, we are trying to predict results within a continuous output, meaning that we are trying to map input variables to some continuous function. 
   ### 1.b Classification  
          In a classification problem, we are instead trying to predict results in a discrete output. In other words, we are trying to map input variables into discrete categories.  
            
              
  ## 2. Unsupervised Learning  
Unsupervised learning allows us to approach problems with little or no idea what our results should look like. We can derive structure from data where we don't necessarily know the effect of the variables.

We can derive this structure by clustering the data based on relationships among the variables in the data.
   
   
# Model and Cost Function  
## Model Representation  
To establish notation for future use, we’ll use x^{(i)}x 
(i)
  to denote the “input” variables (living area in this example), also called input features, and y^{(i)}y 
(i)
  to denote the “output” or target variable that we are trying to predict (price). A pair (x^{(i)} , y^{(i)} )(x 
(i)
 ,y 
(i)
 ) is called a training example, and the dataset that we’ll be using to learn—a list of m training examples (x(i),y(i));i=1,...,m—is called a training set. Note that the superscript “(i)” in the notation is simply an index into the training set, and has nothing to do with exponentiation. We will also use X to denote the space of input values, and Y to denote the space of output values. In this example, X = Y = ℝ.
