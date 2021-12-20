

<p align="center">
  <img src="https://github.com/IzkSensei/Data-Modeling/blob/master/Images/Title.JPG">
</p>
<h1 align="center">Modeling Metrics with Probability Distribution</h1>
<p>Probability distribution can simulate various series of events. Thus, it can be used in order to simulate some events, behavior of the system, or even predict some actions. Different distributions can be used for different usage. In this project, some queries were calculated by some probabilities.
</p>

## Dataset

<p>This dataset consists of the actions of users on an online market including:
<ul>
<li>Action: Click/load
<li>Time
<li>Event ID
<li>Device ID
<li>Page Offset
<li>Post List
<li>Post ID
</ul></a>
<ul>  
</p>

## Problems & Solutions


**1- Probability of clicking on the ad?**

The clicking on ads can be modeled by <ins>Bernoulli distribution</ins> where the user can click or not.

**2- The rank of the first ad that is clicked?**

The rank of the first ad that is clicked on it can be simulated with the  <ins>geometric distribution </ins> where we try until the first success.
  <p align="center">
  <img src="https://github.com/IzkSensei/Data-Modeling/blob/master/Images/Geometric_distribution.JPG">
</p> 

**3- Average distance between clicks?**

For calculating the average distance between clicks of users,  <ins>exponential distribution  </ins>can perform well. It is used for modeling distances between events like distances between clicks.

**4- The probability of clicking on the first 3 ads?**

In order to calculate the probability of clicking on the first 3 results, a  <ins>commutative geometric </ins> distribution is suitable.
  <p align="center">
  <img src="https://github.com/IzkSensei/Data-Modeling/blob/master/Images/Commulative_Geometric_Distribution.JPG">
</p> 



## Data analytics
Some analytics is done on the dataset to know better insights from the dataset in the below. In addition, the Sankey diagram was used in order to demonstrate dataset characteristics.
 
<p align="center">
  <img src="https://github.com/IzkSensei/Data-Modeling/blob/master/Images/Stat1.JPG">
</p> 
<p align="center">
  <img src="https://github.com/IzkSensei/Data-Modeling/blob/master/Images/stat2.JPG">
</p> <p align="center">
  <img src="https://github.com/IzkSensei/Data-Modeling/blob/master/Images/Stat3.JPG">
</p> 


The Sankey diagram with [Plotly](https://plotly.com/python/):

</p> <p align="center">
  <img src="https://github.com/IzkSensei/Data-Modeling/blob/master/Images/Sankey_Diagram.JPG">
</p> 

The HTML file is **[here](https://github.com/IzkSensei/Data-Modeling/blob/master/Sankey.html)**.
