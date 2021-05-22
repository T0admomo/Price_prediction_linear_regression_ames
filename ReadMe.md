## Data Dictionary 

|  Term | Type  | Description  |  
|:-:|:-:|:-:|
|  Lot_Area | float  | total sq_ft of Lot  |   
|  Central Air | int(0/1)  | 0-No AC, 1-Has AC  |   
|  Sq_ft | float  | total sq_ft made from Basement, 1st, and 2nd Fl Sq_ft  |   
|  Has_Garage | int(0/1)  | 0-No Garage , 1-Has Garage  |
|  Sq_ft | int(0/1)  | Lot over 12,000 sq_ft, 0-False, 1-True|
|  Finished_Basement | int(0/1)  | Has Finished Basement, 0-False, 1-True  |
|  SalePrice | float  | Target   |


The goal of this project was to create a Home Appraisel Tool to be used for lead generation in realestate. We aimed to use as few varibaled as possible in order to reduce the number of survey questions needes in the hopes of improving the surveys completion rate.

We began by toying with permutations of 5 features from our given features list. The features selected for our model are explored in the EDA code file and are listed in the Data Dictionary above. The final Performance of our model can be found in code file 'Predictions'.

In general, the model is a success in that its get's a vauation for a home on a minimal number of features, however with our average prediction still off by 42,000 USD we still have to increase the dimesnions and complexity of the model a bit more in order to reduce our error rate.