# Smart-Budget-Analysis-of-Uttar-Pradesh-And-Telangana(VIZ team)-
Budget Analysis of Pre COVID and COVID timelines were done to suggest the U.P and Telangana Governments their next line of action on the areas where more well defined plan is needed

## Headers(Receipts and Expenses) needed for the Analysis from Annual Financial Statements of the two states
-Analysed the economical importance of the headers and subheaders that would be most likely to impact the Budget alloctaion and selected those to do further analysis

-For the Pre COVID timeline, the AFS sheets of past 5 ears were used and to analyse the current COVID timeline projections of several agencies were used 

-Selected those headers and sub headers that were mutually exclusive were exhaustive with respect to the whole budget

## Analysis of the Headers and Sub_Headers inter relationship
-Predicted the next year headers' values with the COVID and without COVID, and then compared the two cases, using 3 and 4 year moving average and linear projection

-Calculated correlation between pairs of headers and sub-headers, which were mutually exclusive and taking the threshold of abs(0.90) to get the appropriate pairs

-The output pairs that were obtained were filtered out by the economic experts to make sense of the relationship becacuse Education allocation and Railways allocation can't have any concrete relationship whereas Education allocation and Family Welfare could have a possible linkage, this was done taking into consideration that correlations doesn't necessarily means causation

-After this, the total number of pairs of headers and sub-headers obtained were 50 and the I performed linear regression and validated the correlation previously obtained with the pearson's coefficient obtained in linear regression

-Performed Visualization and pair plots of those headers and sub-headers for the past five years as well as the predicted values
