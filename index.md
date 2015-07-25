---
title       : Quality
subtitle    : Calculating Quality
author      : Arun
job         : Learning
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction

1.Created a Application ,may be useful for few vendors who wants to calculate the amount of waste they are receiving when they are getting orders from there vendors

2.With the help of this App, they can enter the total number of goods they recived and by removing Waste they can find out what is the % of Good amount

3.Percentage of Good Amount we recived is the Quality


--- .class #id 

## Small Story

Example:

1) A Vegetable shop daily get some stock from there vendors

2)So once the stock is recived the Shop owner would like to measure the amount of Waste he recived from the vendor

3)He would measure the good amount recived and  pay money for good.So that the Vendor would be more carefull for next time

4) Qulaity percent would be calculated to do this. 

I would do a small calculation to illustrate this in the Next slide



--- .class #id 

## Calculation

1)Let us think that the Shop keeper recived 50 kg's of potatoes

2)Out of Which 10 kg is waste. Let us see What is the Quality


```r
TotalPotatoesWeight <- 50
Waste<-10
GoodPotatoesWeight <- TotalPotatoesWeight -Waste
Quality <- (GoodPotatoesWeight/TotalPotatoesWeight)*100
Quality
```

```
## [1] 80
```

So the Quality is calculated as 80%

--- .class #id 

## Conclusion

1) So This how we can use this App .

2)Just giving the 
  
  a)Total Goods 
  
  b)Waste 

Should calculate Quality


Note:This App has nothing to do with real word. Just an Imaginary Stuff

--- .class #id 

## Thank you


