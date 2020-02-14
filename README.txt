Hello!
Welcome to my Github.

You will find a Python3 script in this repository which shows the working of my Hotspot Analysis code.

If you are new to the concept, do give this a read and if you have any questions/comments/suggestions please
feel free to email me on anirudh.ash2594@gmail.com

Thank you and hope you enjoy learning!

----------------------------------------------------------------------------------------------------------

Q. What is a hotspot analysis?
A. Hotspot analysis is a spatial analysis and mapping technique interested in the identification of clustering 
   of spatial phenomena. These spatial phenomena are depicted as points in a map and refer to locations of events 
   or objects.

Q. How is a heatmap different from a hotspot?
A. Excellent question! While a heatmap does the degree or magnitude of occurence of an event, it does not take the
   one most important factor into account, which we have learnt in statistics, 'correlation'. More than often, we 
   know that 'correlation' is that one factor that causes endogeneity and thereby giving rise to a bias in our 
   results. There is no point in working with biased results as your study has gone wrong one step above, when you 
   did not take into account the correlation/autocorrelation factors. A hotspot analysis ensures that all the 
   correlations are accounted for and hence gives us a  more accurrate picture of the subject.

Q. Is that all? 
A. No. Another very important concept, 'statistical significance', is not analyzed by a heatmap. After all, it just
   plots the points we want it to. Statistical significance, as we know, is the like-hood that a relationship
   between two or more variables or features is well defined and not a random occurrence. Hotspot Analysis uses 
   statistical analysis to define areas of high occurrence of an event or an outcome from areas that have a lower 
   occurrence of the same event. 


Q. So how do we test for correlation?
A. We have several tests to study the correlation between explanatory variables and the error terms or the other
   lesser-accounted factors. We first have the Pearson correlation test which measures the linear dependence among
   two variables (x and y). It is also known as the parametric correlation test due it's dependency on how the data
   has been distributed.
   Then we have my favorite, the Spearman correlation which is a non-parametric test and this is a rank-based test
   where we compute the correlation between the rank of x and the rank of y variables.
   