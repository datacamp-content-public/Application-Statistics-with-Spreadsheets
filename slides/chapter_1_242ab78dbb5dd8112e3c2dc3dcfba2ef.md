---
title: Insert title here
key: 242ab78dbb5dd8112e3c2dc3dcfba2ef

---
## Descriptive Statistics

```yaml
type: "TitleSlide"
key: "09d30512a6"
```

`@lower_third`

name: Vikash Singh
title: Descriptive Statistics for Numerical Data


`@script`
Hello everyone, in this video we are going to take a closer look at Descriptive Statistics for numerical data, specifically age levels of ten respondents. Unit of age is in years.  

Let’s start by summarizing our data and the first thing to do is to count the number of observations in our data. We will do that with the Count function. The code is <=count(B3:B13)> , which gives us the value 10 showing that the number of observations is 10. {{}}

In statistics, or measure of central tendency is a central or typical value for a probability distribution. It may also be called a center or location of the distribution. Alternatively, measures of central tendency are often called averages.

The most commonly used measure of central tendency for numerical data are mean and median. {{}} 

Let us talk about mean first. The Mean indicates the average value of the data set. We will use the average function to find out the mean of the data. Using the formula <=AVERAGE(B4:B13)> we see that the mean age of the sample is 57.8 years.{{}} 

Another important measure of central tendency is median, but the main difference of median from mean is that it is more robust and is not influenced by the outliers or extreme values. We will use the average function to find out the mean of the dataset. Using the formula <=MEDIAN(B4:B13)> we see that the median age of the sample is 53.5 years.{{}} 

In this video, we have looked at some of the most commonly used measures of central tendency for numerical data. In our next video, we will take our analysis further and look at Measures of Spread, which are very important descriptive statistics techniques.


---
## Measures of Spread

```yaml
type: "FinalSlide"
key: "31a6f96254"
```

`@script`
Now, let us look at some important measures of spread, namely variance, standard deviation and range. 

For calculating variance, we use the VAR formula, now there are various options in VAR but we have to select VARA which is for sample variance, whereas VARP is for Population Variance. Using the formula <=VARA(B4:B13)>, we notice that the sample variance is 251.3. 

Another measure of spread is standard deviation which can be calculated in two ways. First, we can use the formula <=sqrt(Variance)> and we get standard deviation of 15.9. Another method is to use STDEVA formula for sample standard deviation which will look like <=STDEVA(B4:B13)>

Note that the result is the same for both the methods, i.e, 15.9.

Another measure is range which is basically the spread between the maximum and minimum values in the dataset. The formula for calculating range is <=MAX(B4:B13)-MIN(B4:B13)> which returns the value 47.

