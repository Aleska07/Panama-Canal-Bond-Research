# Panama-Canal-Bond-Research

## We want to extend our heartfelt gratitude to Dr. George Hall and Dr. Thomas J. Sargent for their insights and guidance in this project. We greatly appreciate the commitment, support, and time they have dedicated to us.

### Authors: Aleska Medrano and Thaddaeus Kiker

### Abstract:

This study investigates the price dynamics of Panama Canal Bonds issued in 1906, 1908, and 1911, focusing
on their response to historical events and market conditions in the early 20th century. Using
quantitative economic methods, we analyze time series data and correlations to uncover the influence of World
War I and subsequent global economic fluctuations on bond prices. Our research poses three key questions:
(1) Do bond price behavior correlate with historical events during World War I?
(2) Is there a significant divergence in bond price behaviors over time and in response to similar events?
(3) Why did the Panama Canal Bonds show differing trajectories in their price behavior?
On this report we focused on asnwering the 3rd question. For this purpose, we used Panama Canal Bonds and compared them to Railroad Bonds and Liberty Loans at the end of World War I. 
The code and corresponding graphs can be find the attached files as jupyter notebooks (.ipynb)
The original data set can be found here: https://github.com/jepayne/US-Federal-Debt-Public/tree/master.

## Historical Overview of the Panama Canal Bonds:
The US began the construction of the Panama Canal on May 4th, 1904, and concluded it on August 15th, 1914. However, this project was significantly costly, and the government needed to raise debt to finish it; thus, they issued four series of bonds to serve this purpose: the 1906, 1908, and 1911 series, plus the conversion bonds. Nonetheless, this project focused on the regular bonds because there was no available data on the behavior of the conversion bonds.

1906: The 2%  Panama Canal Bond isued in 1906 had a term to maturity of 30 years(1906-36). Sold to the highest bidder, it caused sales of a group of previous bonds called "Consol 2s" (then quoted at 103.25) and the retirement of circulation accounts. The provision limited the retirement to $3,000,000 per month and prevented the market price of Consol 2s from declining to par. To provide support, the Secretary called for $10,000,000 in special Government bonds and created a market demand for Panama 2s. The average price realized for the $30,000,000 Panama 2s of 1916-1936 was 104.036. To avoid a money stringency incident, all purchasing banks were permitted to retain one-third of the purchase money as Government deposits. This also had a stimulating effect on the price bids for the bonds. 

1908:  The $30,000,000 Panama Canal 2% bonds with a term to maturity of also 30 years (1918-38) offered in December were readily absorbed by the banks, and the Government bond market closed the year with all issues firm. It looked like the confidence in the project has a big incentive for investors to purchase more of the Panama Canal Bonds.

1911: The treasury offered $50,000,000 Panama Canal 3s, dated June 1, with a term to maturity of 50 years. The bids aggregated $212,085,200, and the average price realized was 102.5825. This produced a premium of $1,291,274 and made the Treasury’s actual interest rate of the transaction 2.9019%. Within a year after their issue, the Panama 3s sold as high as 103 ¼, and in 1945, thirty-four years later, they were quoted as high as 135 ½, yielding 0.65%, solely because they were fully tax-exempt. This last bond series issued shows some clear differences in it's structure that made it attractive to investors; thus, the expectation would be for it to out perform the previous Panama Canal Bonds. Yet, through our time series plot somparing the three bonds it is clear that this particular bond behaves in a different way to its competitors but it also falls on a much bigger scale than its counter parts between 1916 and 1924. 

This leads us to try to investigate the divergence in behaviour by comparing it with other bonds issued in a similar time and circumstance.

## The Panama Canal Bonds and the Railroad Industry
In the 1900s, the Railroad industry had reached good momentum, given that most of its systems were taking shape and running. Thus, to finish existing projects, it made sense for the federal government to raise debt. Therefore, to provide an accurate overview of the market context of the time, we used a dataset that gives the monthly price for high-grade American railroad company bonds when the Panama Bonds were issued.
Looking into the time series plots, we found the relationship between the 1906 Series canal bond and the Railroad Bonds Index fascinating because before the US Railroads were nationalized in December 1917, they were well correlated positively with the canal bond price. However, things got askew during the nationalized period, but then after 1924, they seemed to have a certain level of negative correlation. Further regression analysis is required to determine the correlation best fits the two data sets.

Nonetheless, it is important to note that the Railroad industry bonds were very closely correlated with the price behavior of the 1906, and 1908 bonds but again, the 1911 bond appears to be an outlier. Furthermore, we review literature and record from the time the bonds were issued in the book "Concerning U.S. Government Securitie"s by Charles Frederick Childs published in 1947 and some new questions arised, as shown below:

## Is the answer to the divergence of the Panama Canal Bonds found in 1914?
The date the Secretary of the Treasury fixed for opening the Federal Reserve Banks for business was November 16th, 1914. For this purpose, the country had been divided into twelve districts for the early launching of the new system. However, the difficulties of the undertaking were aggravated by economic disturbances occasioned by WWI, which extended to every part of the country and might have caused skeptisism in investors about the national debt and were pulling back from other existing bonds like the Liberty or Victory bonds, but thei situation didn't seem to affect the Panama Canal Bonds that much. 

Conditions of uncertainty and perplexity confronting the Board when it began its work in August had a considerable bearing on the policy pursued.  The outbreak of hostilities in Europe immediately led to a severe rupture of international financial relationships throughout the commercial world, involving the temporary breakdown of export trade and the collapse of the financial markets, resulting in a shock to the credit system. European holders of American securities sought to sell them in the New York Market, which was demoralized. Prices declined alarmingly rapidly, and the country was exposed to a severe and disastrous drain of gold. 

Additionally, on February 2nd, 1920, Davis F. Houston made a comment that gives some insight on the price divergence between other industry bonds and the Panama Bonds; however, this is not the full explanaition of the story: 

"The Liberty bonds and Victory notes were deeply affected because they were selling below par-value, but it seems that the Panama Canal 1906 bonds were different not only because of the divergent price paths but also because its construction was concluded in 1914, so this investment was going to be backed up by revenues from the Canal operations. Thus, amid economic distress, investors would favor a reliable revenue stream from the Panama Canal instead of an uncertain declining bond."

## Is the answer found in 1917?
There is no doubt that starting in 1914 WWI took great importance in the map and the new question for the United States was how to finance it. Furthermore, there were three main options the government could've taken given the new Federal Reserve that was established in 1913. (1) Raising taxes, (2) Borrowing from the public, and (3)printing money. As an earlier example, durng the civil war the governemnt had simply printed greenbacks but this was not fit because of the gold standard at the time. However, Treasury Secretary William Gibbs McAdoo thought that finance about 50% from taxes and 50% from bonds would work well. Thus, in October 1917 Congress responded to the call for higher taxes with the War Revenue Act. This act increased the personal and corporate income tax rates and established a new excercise, excess-profit, and luxuxry taxes. The tax rate for an income of $10,000 with four exemptions (about $140,000 in 2003 dollars) went from 1.2 percent in 1916 to 7.8 percent. For incomes of $1,000,000 the rate went from 10.3 percent in 1916 to 70.3 percent in 1918. These increase in taxes and the increase in nominal income raised revenues from $930 million in 1916 to $4,388 million in 1918. Federal expenditures, however, increased from $1,333 million in 1916 to $15,585 million in 1918. A huge gap had opened up that would have to be closed by borrowing. Thus, Liberty Bonds were created. Below we will take a closer look into the LIberty Bonds. 

## Did taxes directly affect the Panama Canal 1911 Bond?
Diving a little bit deeper into the specifics of the 1911 series Bond. It is interesting that wihtin a year after their issue date, the Panama 3s sold as high as 103.125 and thirty-four years later reached a high of 135.5, yielding .65%, solely because they were FULLY TAX-EXEMPT. In addition, the omission of the priviledge to use these bonds as a basis for national bank circulation put them squarely upon an investment basis. The story suggests that the rapid rise in taxes does not affect the price of the 1911 Bonds because they were tax extempt so another type of correlation must exist. 

## Relationship between the Liberty Bonds and Panama Canal Bonds
World War I began in Europe in 1914, and this same year the Federal Reserve System was established. During the three years it took for the United States to enter the conflict, the Fed had completed its organization and was in a position to play a key role in the war effort. However, the government didnlt have the liquidity to make a big entrance so they had to borrow from the generla public. Specifically for this war, the federal government relied on a mix of one-third new taxes and two-thirds borrowing from the general population. Very little new money was created. The borrowing effort was called the “Liberty Loan” and was made operational through the sale of Liberty Bonds. These securities were issued by the Treasury, but the Federal Reserve and its member banks conducted the bond sales.

In the plots we created (which you can find in the file called liberty bonds) you can see that the 1st series liberty loan bonds stand out against 2nd-4th (top plot), yet when comparing the 1st and 4th series to the 1906 canal bond prices, we see that the 1906 Panama Canal bond was much less affected by the onset of the global depression. We believe that the cause of this difference in price is related to the different origins of money based upon which the U.S. Treasury promised to use to repay these bonds. Specifically, the archived Annual Reports of the Isthmian Canal Commission (e.g. the one from 1914), and our understanding from these is that the United States government pledged the revenues generated from tolls collected from vessels using the canal as repayment for the bond. Hence, we suspect the Panama Canal Bonds were perceived as more stable due to their association with a significant source of predictable income. In contrast, we wonder if the Liberty Bonds were more impacted by the global depression because they were closely tied to wartime financing and post-war economic adjustments, which introduced significant uncertainty. Overall, we think that investor preferences for stability and the selling pressure on Liberty Bonds during economic hardship further exacerbated their decline in comparison to the canal bonds. 

## Conclusion

In conclusion, we found that there are three aspects that make the panama canal bond intriguing. The correlation of the Panama Canal Bond Prices with historical events during World War One, the divergence in behavior between the different Panama Canal Bond Prices over time and in response to various aforementioned events, and the divergence in behavior between some of the Panama Canal Bonds and the Railroad Bond Price Index and Liberty Loans towards the
end of World War I which continued into the short global depression which followed that war.

Citations: 
Concerning U. S. government securities: A condensed review of the nation’s currency, publi by Childs, Charles Frederick. Concerning U. S. Government Securities: A Condensed Review of the Nation’s Currency, Publi by Childs, Charles Frederick - Amazon.ae. (n.d.). https://www.amazon.ae/Concerning-U-Government-Securities-Condensed/dp/1258280485 
David F. Houston (1920 - 1921). U.S. Department of the Treasury. (2020, April 23). https://home.treasury.gov/about/history/prior-secretaries/david-f-houston-1920-1921 
Macaulay, F. R. (1938, January 1). Some theoretical problems suggested by the movements of interest rates, bond yields and stock prices in the United States since 1856. NBER. https://www.nber.org/books-and-chapters/some-theoretical-problems-suggested-movements-interest-rates-bond-yields-and-stock-prices-united 
Railroads in the late 19th century: Rise of industrial america, 1876-1900: U.S. History Primary Source Timeline: Classroom materials at the Library of Congress: Library of Congress. The Library of Congress. (n.d.). https://www.loc.gov/classroom-materials/united-states-history-primary-source-timeline/rise-of-industrial-america-1876-1900/railroads-in-late-19th-century/#:~:text=By%201900%2C%20much%20of%20the,the%20railroads%20was%20fully%20realized. 
Sutch, R. (n.d.). Liberty bonds. Federal Reserve History. https://www.federalreservehistory.org/essays/liberty-bonds 
Period 6: 1865-1898 (AP US history). Period 6: 1865-1898 (AP US History) | Gilder Lehrman Institute of American History. (n.d.). https://www.gilderlehrman.org/ap-us-history/period-6?modal=%2Fhistory-resources%2Fessays%2Ffinancing-transcontinental-railroad 
Panama Canal Loan: Herbstman-Collection. herbstman. (n.d.). https://www.theherbstmancollection.com/panama-canal-loan 




