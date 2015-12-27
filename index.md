---
title       : Heart Disease Prediction
subtitle    : 
author      : Bhavana Shah
job         : December 27, 2015
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Abstract
- Cardiovascular diseases (CVDs) or Heart Diseases, are disorders of the heart and blood vessels and include coronary heart disease, cerebrovascular disease, rheumatic heart disease and other conditions. 

- It is number one cause of death in adults globally. 

- People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidaemia or already established disease) need early detection and management using counseling and medicines, as appropriate.

- Medical diagnosis is an important but a complex task that demands high accuracy.
 
- Automation of diagnosis has huge advantage that can aide healthcare providers in efficiently identifying and providing the treatment as needed in a timely manner.
 

<a href = http://www.who.int/cardiovascular_diseases/en/>WHO Site Link</a>

--- 

## Application & Features
- The application is built using Shiny app. It predicts heart disease using Random Forest Algorithm.

- The data is obtained from  <a href = https://archive.ics.uci.edu/ml/datasets/Heart+Disease>UCI Machine Learning Repository.</a>
 
- This app is using 'processed.cleveland.data'. This dataset contains 76 attributes, out of which only a subset of 14 of them have been used. 

- Prior to building the Random Forest model, the data is split into training (70%) and testing sets (30%).

- Random Forest number of trees can be selected by the user (range 100-1000). The default is 500. The model gets dynamically re-built on changing the number of trees and updates all the visualizations plots.

- Data can be viewed, searched and sorted from the 'Data' Tab.

- Correlation matrix and pairs plot are displayed for data exploration purposes in the 'Exploration' Tab.

--- .class #Id 

## UI & Visualization
 <img src= "./assets/img/uiSS.png" height='275' width='900'/> 
 
#### Visualization for Error rate
<img src="assets/fig/unnamed-chunk-1-1.png" title="plot of chunk unnamed-chunk-1" alt="plot of chunk unnamed-chunk-1" style="display: block; margin: auto;" />

--- .class #Id 

## Future Enhancements
<div class="columns-2">
  <img src= "./assets/img/futureScope.png" height='550'/> 

<p>

In order to advance this app:<br/><br/>

- Obtain and utilize large datasets.<br/><br/>

- Build & compare using additional machine learning algorithms such as SVM, knn.<br/><br/>

- User prediction screen (as shown in image) for prediction against various models.<br/><br/>

</p>
</div>



