# Solar

In this project, I downloaded datasets from Google's Project Sunroof for solar, U.S. Government's 2010 Census for demographics, and the 
IRS for income data. The intent of the analysis was to figure out if there are any relationships between the amount of solar being 
produced and any socioeconomic and/or demographic factors. The datasets are all linked by U.S. Postal (ZIP) codes.

I assumed that since California is a very liberal state home to wealthy individuals and technologically advanced companies, that it 
would have more progress on solar. The California government (as well as the Southwest region) offers many incentives to not only 
individuals but also businesses to invest in solar. Thus, I hypothesized that the solar production and installations in California 
would be higher than other parts of the nation. Similarly, another hypothesis is that ZIP codes with an average higher income have 
made further progress on solar than ZIP codes with a lower average income. I used linear regression, a correlation matrix, and k-means 
clustering as part of the analysis to determine if there are any relationships.

The analysis shows that there was no simple linear relationship between solar production and average adjusted income of that ZIP code. 
Interestingly, though, the Asian population is moderately correlated to existing installations of solar. There is no evidence that 
Asian households or Asian owned buildings are the ones investing in solar. It could be due to the fact that there are more Asians in 
higher cost of living areas such as Los Angeles and the San Francisco Bay Area. Lastly, the results shows that the states that have the 
most to gain from solar (in terms of potential kilowattage) are indeed the ones that have made the most progress so far.

This repository contains the final report and the code (Jupyter notebooks) used to generate the results. 
