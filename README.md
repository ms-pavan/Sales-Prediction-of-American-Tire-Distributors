# ReinventTheWheel

Problem Statement:   

American Tire Distributors (ATD) relies on intelligent strategies on inventory planning and demand prediction, so that they can smartly stock items at each DC and ensure they meet customers’ needs. For ATD, the key to satisfying this demand for replacement tires is individual distribution centers (DC) footprint. Spread across the entire U.S., each DC supports the needs of its nearby customers.

Required solution:    
Predict how many tires are in demand for each DC. Specifically, how many tires of different kinds are in demand for each DC.

Data:    
 
a. Vehicle Registration Data     
    Age, make, model of the car    
    Able to merge with Sales data on ZipCode level    
b. Sales Data    
    customers (tire shops, car dealerships, tire category etc) purchase history      
   
Approach:  
Worked on Data Exploratory Analysis to understand distribution and sales of different DC.   
Merged the Sales Data and Vehicle Registration Data sets for meaningful results in demand prediction.  
Used Light GBM model and predicted the demand of different types of tires for each DC. 
