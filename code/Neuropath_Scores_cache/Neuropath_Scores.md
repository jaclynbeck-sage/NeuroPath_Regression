---
title: Logistic Ordinal Regression of ROSMAP DLPFC Expression to NeuroPath Scores
output: html_notebook
---
Date of analysis update: "Wed May  6 19:15:47 2020"





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
## Time difference of 1.019349 mins
```

```
## Time difference of 51.98983 secs
```

```
## Time difference of 49.98646 secs
```

```
## Time difference of 49.19726 secs
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
[Github](https://github.com/jgockley62/NeuroPath_Regression/blob/38fbd2dda9c8b282b922e6c111d69c1095339603/code/Neuropath_Scores.Rmd)


