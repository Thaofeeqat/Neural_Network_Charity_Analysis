# Neural_Network_Charity_Analysis


# OVERVIEW

This analysis was carried out for the main purpose of helping Alphabet Soup’s business team to predict where to make investments,
Pandas and the Scikit-Learn was use in preprocessing the csv file that was sent to the foundation to  compile, train, and evaluate the dataset.

# RESULT

* Q1
  The Alphabet Soup application type was used as the target of the model in this analysis.
  
   ![Image Here](https://github.com/Thaofeeqat/Neural_Network_Charity_Analysis/blob/main/Images/app.png)
   
* Q2

  The Government organization classification column was used as the features of the model in this analysis.
  ![Image Here](https://github.com/Thaofeeqat/Neural_Network_Charity_Analysis/blob/main/Images/class.png)


* Q3

  The Variables that were droped in the process are shown below;
  
  ![Image Here](https://github.com/Thaofeeqat/Neural_Network_Charity_Analysis/blob/main/Images/drop.png)
  
 * Q4
      
      
     Using the Random forest classifer showed the 100% accuracy in the analysis and at this point the hidden layer1 was set to 75 and the hidden layer2 was set to 25 giving the parameters as 1900, and the epoch  training regimen was on 50.
     
     
     ![Image Here](https://github.com/Thaofeeqat/Neural_Network_Charity_Analysis/blob/main/Images/Random.png)
     
 The evaluation  of the model using test data  shows 0.99% accuracy.
 
    ![Image Here](https://github.com/Thaofeeqat/Neural_Network_Charity_Analysis/blob/main/Images/Randomb.png)
    
    
       * The hidden layer1 was reduced to 55 and hidden layer2 was increased to 35, and the epoch traing regimen was increased on 60. The evalutaion of the model run still shows as 0.99% accuracy 

       * The hidden layer1 was set to 75 and hidden layer2 was reduced to 20, and the epoch traing regimen was increased on 100. The evalutaion of the model run still shows as 0.99% accuracy 

  
 
    
