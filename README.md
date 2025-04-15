# Human Development Index 2022 Analysis

## **Brief Overview:**

The Human Development Index (HDI) was developed by the United Nations Development Program (UNDP) to assess the well-being of a country’s population. It combines three key dimensions: life expectancy, education, and standard of living. According to the UNDP, “the HDI is the geometric mean of normalized indices for each of the three dimensions.”

To explore the HDI in more detail, including methodology and access to raw data, you can visit the [UNDP website](https://hdr.undp.org/data-center/human-development-index#/indicies/HDI).

Each year, countries recognized by the United Nations are ranked based on their HDI scores. For this analysis, I focused on two components that contribute to the HDI and investigated their relationship to countries’ overall HDI rankings:

1.	**Education Gap** (calculated as Expected years of schooling – Average years of schooling).
2.	**Gross National Income (GNI) per capita** (constant 2017 PPP$).

## **Key Concepts:**

+	**Education Gap** indicates whether a population reaches their knowledge potential. A difference of zero would indicate that individuals spend as many years studying as it is expected in that country. Larger differences indicate that the country’s wealth is not being translated into education opportunities.

+	**The Gross National Income (GNI) per capita** (constant 2017 PPP$) describes the average income per person in a country in a year, adjusted for inflation and differences in cost of living across countries based on the year 2017.

The most recent HDI calculated is of the year 2022 and the open access data can be assessed at the [UNDP website](https://hdr.undp.org/data-center/documentation-and-downloads).

## **Main questions:**

To understand how Education Gap and GNI related to the HDI rank of those countries, I asked two primary questions:

+ Are the countries ranked higher in the HDI rank also the wealthiest?
+ Does higher human development correspond to lower Education Gap? 

For the analysis, I used the UNDP’s classification of countries into four groups:

+ Very High Human Development
+ High Human Development
+ Medium Human Development 
+ Low Human Development

## **Results:**

![Dashboard](https://github.com/lpasqualette/portfolioHDI/blob/master/HDIPortfolio.png)

Several insights emerged from the analyses. Regarding to the two central questions:

+ Countries ranked higher in the HDI rank of 2022 tend to be wealthier.

+ Higher human development does not necessarily correspond to lower Education Gap. Contrary to the hypothesis, countries from the Very High Human Development group (average 4.4 years) did slightly worse than countries belonging to the High Human Development Group (4.0).

Other relevant observations:

+ Countries classified as Very High Human Development exhibit not only the greatest variability in Education Gap (SD = 2.3), but also in wealth levels (SD = $22K). 

+ Countries classified as High Human Development had the lowest variability in the Education Gap years (SD = 1.7) when compared to Medium and Low Human Development Groups (SD = 1.9).

+ Inference: greater financial resources do not always translate into more years of education in those countries. 

The exact reasons for those discrepancies have to be seen case by case as showcased in two examples:

+ 🇹🇷 Türkiye has a wide Education Gap despite being classified in Very High Human Development group. This stems from multiple social inequality issues in the country related to gender, socioeconomic status, regional challenges and immigration [(OECD, 2023)](https://www.oecd.org/content/dam/oecd/en/publications/reports/2023/04/taking-stock-of-education-reforms-for-access-and-quality-in-turkiye_8ef9c5a2/5ea7657e-en.pdf).

+ 🇸🇸 South Sudan presents low Education Gap because of universally limited access to education rather than equitable opportunity. The Expected Years of Schooling are only 5.6 years, which is very low when compared to Very High Human Development countries, such as Switzerland (16.6) or Iceland (19.1), for example. In addition, the ongoing humanitarian crises exacerbates social issues, as 73% of its population require  humanitarian assistance [(Windle Trust International, 2023)](https://www.windle.org.uk/south-sudan-education-system). 

## Key Conclusions:

+ Wealth Strongly Correlates with HDI Rank

         Countries with higher HDI rankings tend to have higher Gross National Income (GNI) per capita, confirming a strong relationship between national wealth and human development.

+ Education Gap Doesn’t Decrease Linearly with Human Development

        Contrary to expectations, countries in the Very High Human Development group had a slightly larger average Education Gap than those in the High Human Development group.

       This suggests that economic prosperity and high HDI do not always equate to educational equality or fulfillment of educational potential.

+ High-Income Countries Show More Variability

        Very High Human Development countries displayed the greatest variability in both GNI and Education Gap, indicating diverse internal conditions despite similar HDI categories.

        This highlights that within-group disparities are significant and that aggregate HDI scores may mask underlying inequality.

+ Education Gap Can Be Misleading Without Context

        A low Education Gap does not necessarily reflect equal educational opportunity:

            In South Sudan, the small gap exists because both expected and actual years of schooling are very low due to systemic limitations.

            In contrast, Türkiye has a large gap despite its high HDI classification, illustrating how social and structural inequalities influence education access.

## Implications:

+ Targeted social policies are needed to address the qualitative and distributional aspects of education and wealth.

+ Cross-country comparisons should account for context-specific factors like regional inequality, gender disparity, and humanitarian crises.