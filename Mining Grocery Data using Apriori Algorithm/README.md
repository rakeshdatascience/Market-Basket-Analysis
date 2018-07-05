
## Market Basket Analysis on Grocery Data
Please click [here](https://github.com/rakeshdatascience/Market-Basket-Analysis/blob/master/Mining%20Grocery%20Data%20using%20Apriori%20Algorithm/Notebook/Apriori%2Balgorithm(Python%2BNotebook).ipynb) to view the project done in Python & click [here](https://github.com/rakeshdatascience/Market-Basket-Analysis/blob/master/Mining%20Grocery%20Data%20using%20Apriori%20Algorithm/Notebook/Apriori%20algorithm(R%20codes).ipynb) to view the project done in R.





<p align="center">
  <img src="https://github.com/rakeshdatascience/Market-Basket-Analysis/blob/master/Mining%20Grocery%20Data%20using%20Apriori%20Algorithm/Images/c0a130192ac39588b9adedad3bcb2abe.jpg",alt="neofetch" align="middle" height="200px">
  </p>






## Objective
Market Basket Aalysis is widely used by superstores for the following things-
#### 1. `Cross Selling`
#### 2. `Product Placement`
#### 3. `Customer Segmentation`
#### 4. `Affinity Promotion`

So keeping the above mentioned importances of Market Basket Analysis, the experiment was conducted on Grocery data to come up with sound business decisions to scale up the revenue.

## Tools & Algorithm used
The experiment was done in both Python & R using `Apriori Algorithm`

## Dataset description
The data was collected from an online source. The Grocery data is typical transaction data tabuled in sparse matrix format.The dataset has 9836 transaction instances(Rows), 32(columns) items appearing in sparse matrix form.

Please Click [here](https://github.com/rakeshdatascience/Market-Basket-Analysis/blob/master/Mining%20Grocery%20Data%20using%20Apriori%20Algorithm/Dataset/Grocery.csv) to view the dataset.

##### Have a glimpse of the dataset









![alt-text](https://github.com/rakeshdatascience/Market-Basket-Analysis/blob/master/Mining%20Grocery%20Data%20using%20Apriori%20Algorithm/Images/Capture%60.PNG)



## Code snippets( Analysis done in Python)

Code snippets given below are takesn from Python notebook


To install mlxtend for Ariori Algorithm please type 
`!pip install mlxtend`

### Import necessary libraries





<p align="center">
  <img src="https://github.com/rakeshdatascience/Market-Basket-Analysis/blob/master/Mining%20Grocery%20Data%20using%20Apriori%20Algorithm/Images/python%201(import%20lib).PNG",alt="neofetch" align="middle" height="50px">
  </p>



### Read the dataset



<p align="center">
  <img src="https://github.com/rakeshdatascience/Market-Basket-Analysis/blob/master/Mining%20Grocery%20Data%20using%20Apriori%20Algorithm/Images/p-2.PNG",alt="neofetch" align="middle" height="150px">
  </p>
  
  



### Dimension of the dataset

<p align="center">
  <img src="https://github.com/rakeshdatascience/Market-Basket-Analysis/blob/master/Mining%20Grocery%20Data%20using%20Apriori%20Algorithm/Images/p3.PNG",alt="neofetch" align="middle" height="40px">
  </p>
  



### Basket

First basket after dummy encoding the variables



![alt-text](https://github.com/rakeshdatascience/Market-Basket-Analysis/blob/master/Mining%20Grocery%20Data%20using%20Apriori%20Algorithm/Images/p4.PNG)





### Apply Apriori Algorithm with min_support 0.003


  ![alt-text](https://github.com/rakeshdatascience/Market-Basket-Analysis/blob/master/Mining%20Grocery%20Data%20using%20Apriori%20Algorithm/Images/p5.PNG)
  
  

### Build  association rules with lift >= 1 & confidence >=0.5

 ![alt-text](https://github.com/rakeshdatascience/Market-Basket-Analysis/blob/master/Mining%20Grocery%20Data%20using%20Apriori%20Algorithm/Images/p7.PNG)



## Code snippets( Analysis done in R)

### Import necessary library

please ensure that `arules` is installed in R console before further diving

<p align="center">
  <img src="https://github.com/rakeshdatascience/Market-Basket-Analysis/blob/master/Mining%20Grocery%20Data%20using%20Apriori%20Algorithm/Images/R1.PNG",alt="neofetch" align="middle" height="80px">
  </p>




### Read the data & find the summary

![alt-text](https://github.com/rakeshdatascience/Market-Basket-Analysis/blob/master/Mining%20Grocery%20Data%20using%20Apriori%20Algorithm/Images/R2.PNG)

### Let's inspect first seven transactions


<p align="center">
  <img src="https://github.com/rakeshdatascience/Market-Basket-Analysis/blob/master/Mining%20Grocery%20Data%20using%20Apriori%20Algorithm/Images/R3.PNG",alt="neofetch" align="middle" height="180px">
  </p>



### Let's see what we get with support of 10%

![alt-text](https://github.com/rakeshdatascience/Market-Basket-Analysis/blob/master/Mining%20Grocery%20Data%20using%20Apriori%20Algorithm/Images/R4.1.PNG)

#### Output



![alt-text](https://github.com/rakeshdatascience/Market-Basket-Analysis/blob/master/Mining%20Grocery%20Data%20using%20Apriori%20Algorithm/Images/R4.PNG)




### Top 5 frequently occurring items


![alt-text](https://github.com/rakeshdatascience/Market-Basket-Analysis/blob/master/Mining%20Grocery%20Data%20using%20Apriori%20Algorithm/Images/R6.PNG)


![alt-text](https://github.com/rakeshdatascience/Market-Basket-Analysis/blob/master/Mining%20Grocery%20Data%20using%20Apriori%20Algorithm/Images/R5.PNG)



### Find the basket with support 0.07 & confidence 0.35

![alt-text](https://github.com/rakeshdatascience/Market-Basket-Analysis/blob/master/Mining%20Grocery%20Data%20using%20Apriori%20Algorithm/Images/R7.PNG)


#### Output

![alt-text](https://github.com/rakeshdatascience/Market-Basket-Analysis/blob/master/Mining%20Grocery%20Data%20using%20Apriori%20Algorithm/Images/R8.PNG)

### Let's inspect top 6 associations by lift(descending order)
![alt-text](https://github.com/rakeshdatascience/Market-Basket-Analysis/blob/master/Mining%20Grocery%20Data%20using%20Apriori%20Algorithm/Images/R10.PNG)










