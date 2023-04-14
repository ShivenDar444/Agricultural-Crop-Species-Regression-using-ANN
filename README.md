# Agricultural-Crop-Species-Regression-using-ANN  

Requirements: 

To run this project, we will need the following:

-Python 3.x 

-TensorFlow 

-Pandas 

-NumPy 

-Matplotlib 



Abstract:


We will try to predict the crop yield of various samples based on the item, average rainfall, amount of pesticides in tonnes and average temperature.
  
Objectives:

1)The main objective of our project is to predict the yield of the crop.  

2) We can decide the prices of crops based on supply and demand. 

3) Be ready for less supply in advance preventing cost inflation 

4) Taking a look at the impact of Average rainfall on the crop yield. 

5) How much pesticides are optimum for different type of crops.  

Dataset: 

The dataset used for this project is a publicly available dataset from the UCI Machine Learning Repository. The dataset contains information on different crops such as corn, soybeans, wheat, and oats, and includes information such as the number of days from planting to maturity, temperature, precipitation, and fertilizer usage.



Instructions: 

1.Clone this repository to your local machine.
 
2.Install the required packages by running the following command in your terminal: pip install tensorflow pandas numpy matplotlib
 
3.Navigate to the directory where you cloned the repository and run the crop_yield_regression.py file.
 
4.The program will train the ANN on the dataset and save the trained model to a file named crop_yield_model.h5.
 
5.The program will then use the trained model to make predictions on a test set and output the results to the console.
 
6.To visualize the results, run the plot_results.py file. This will generate a plot of the actual crop yields versus the predicted crop yields.
 
  
IV) RESULTS  
 
The overall accuracy was 94.99%. In an attempt to improve it, another ”bigger” ANN was tried. Besides the normal layers, a dropout layer was added. A dropout layer only works during the training and randomly ”cuts off” (sets to zero) some inputs. It is expected that dropout layers reduce the risk of overfitting. The optimiser and loss function were used: ‘Adam’ and the ‘mean squared error’, respectively. The network was also trained for 100 epochs. The overall accuracy was 94.99%, thus the improvement was not much
