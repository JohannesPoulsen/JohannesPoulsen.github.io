---
layout: default
---
# Assignment 2

## Introduction to the dataset
This datastory explores the patterns in crime across San Francisco over a period of 10 years. This uses **the San Francisco Police Department Crime Dataset**, that contains detailed reports of incidents from 2014 to 2024. The dataset includes information such as crime categories, coordinates (latitude/longitude), districts and more. 

By analysis of this data, we want to cover how crime patterns have changed over time. In particular, this datastory will cover the patterns of crimes in the **drug/narcotic** category. It shows how drug-related crime has changed over time, where it happens most in the city, and how it differs between neighborhoods.

To shows this we have made three different visualizations:
1. A bar chart that shows the frequency of drug crimes per year in San Francisco.
2. A heatmap video that shows the development of drug crime rates in different locations across San Francisco over the 10 years.
3. An interactive Bokeh chart that compares the drug crime rates in the different districts.

## Bar chart
The bar chart below illustrates the annual number of reported drug and narcotic-related crimes in San Francisco from 2004 to 2024.
![Drug crimes per year](pages/drug_crimes.png)
We can see that the number of drug-related crimes peaked in 2009 with nearly 12,000 cases. Since then, there's been a big drop. In recent years, the number has stayed around 4,000. 

One reason for this drop could be a change in the law. In 2011, California made marijuana possession a less serious offense, which meant people were no longer arrested for carrying small amounts. This change led to a big drop in drug arrests across the state about 86% fewer marijuana arrests that year.[^1]

According to **The San Francisco Standard**, San Francisco’s approach to drug use changed. Instead of focusing on punishment, the city started treating drug issues more as a public health problem. [^2]. According to **stopthedrugwar.org** the police began spending more time on serious crimes, which also helped lower the number of drug-related arrests [^3].


## Heatmap video
Below is a heatmap showing the development in drug crime counts in San Francisco. 
<iframe src="pages/sf_heatmap_with_time.html" width="800" height="600"></iframe>
If you compare the early years, like 2009, with later years like 2018 in the Tenderloin district, you will notice the red zones (which show more activity) fade out. This supports what we saw in the bar chart before. 

## Boteh interactive chart
The Boteh chart below gives you the opportunity to see drug crime counts in the different districts of San Francisco from 2004 to 2024. 
<iframe src="pages/barplot.html" width="800" height="600"></iframe>
You can click on a district to focus on it. This makes it easy to compare drug crime across neighborhoods and see how things have changed over time. For example, if you select **Taraval** and **Tenderloin**, you’ll see that **Taraval** had more drug crimes before 2018, but after that, **Tenderloin** had higher numbers.

## Discussion

## References
[^1]: https://www.cjcj.org/news/blog/reform-cuts-marijuana-possession-arrests-86-in-2011-upends-california-drug-policing
[^2]: https://sfstandard.com/2023/06/12/why-san-francisco-does-not-police-open-drug-use/
[^3]: https://stopthedrugwar.org/chronicle/2011/oct/31/sf_de_facto_drug_decriminalizati


[Link to all notebooks](./pages).