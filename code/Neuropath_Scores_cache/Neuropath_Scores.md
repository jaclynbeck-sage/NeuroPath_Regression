---
title: Logistic Ordinal Regression of ROSMAP DLPFC Expression to NeuroPath Scores
output: html_notebook
---
Date of analysis update: "Wed May  6 22:30:52 2020"



#### Pull Data

```
## 
## TRUE 
##  632
```

```
## 
## TRUE 
##  632
```

```
## 
## TRUE 
##  632
```

#### Setup and Run Models



```
## Time difference of 1.052291 mins
```

```
## Time difference of 54.19447 secs
```

```
## Time difference of 51.27036 secs
```

```
## Time difference of 50.54385 secs
```

```
## [1] "Significantly associated genes by Neuropath Score: "
```

```
## 
## BRAAK CERAD COGDX DCFDX 
##   938   638   520   643
```

```
## [1] "Frequency of Gene Across Significance to Neuropath Score: "
```

```
## 
##   1   2   3   4 
## 854 496 151 110
```

```
## [1] "Significantly associated genes by Neuropath Score with an Odds Ratio < 1: 1358"
```

```
## [1] "Significantly associated genes by Neuropath Score with an Odds Ratio > 1: 1381"
```

```
## [1] "Significantly associated genes by Neuropath Score with an Odds Ratio > 1 by Score Type: "
```

```
##        
##         BRAAK CERAD COGDX DCFDX
##   FALSE   501   314   235   308
##   TRUE    437   324   285   335
```



### Store files in synapse


### R Source Code
[Github](https://github.com/jgockley62/NeuroPath_Regression/blob/9c8d5c66ffc5cef1f563494df2760f4089171b66/code/Neuropath_Scores.Rmd)


