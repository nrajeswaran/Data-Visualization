## Introduction
The tech world has evolved over years and today we stand in the era where day to day life is dependent on the technology- be it a smart phone or any other smart device. Every other day we get to know new gadgets being introduced by hundreds of tech firms worldwide. On a simple note, if you take a smart phone we have many manufactures but very few run their show successfully. To prove that, we have amazon Fire phone which has failed to make its spot in the tech world. This might be due to the reason that consumers are bored with the technology inventions which does not really stand out of the crowd. 

The below image is based on the survey conducted by Accenture among 28,000 consumers worldwide on their interests to purchase new products. This explains that the purchase intent rate of the consumers planning to purchase devices like smartphone, laptop, tablet, etc., in the year 2016 and compares with the previous year to analyze the percentage of change over. With this information, the chart claims the fact that there is a decline in interest in products like smartphone, laptop, television, etc., hence makes a fact that consumers are bored of technology. 

![Alt text](https://github.com/nrajeswaran/Fall17_DataViz/blob/master/Redesign_Project/Original_Work.png)

## Critique on the original work

  - The chart clearly showcases the fact that the amount of research undergone for this article is very trivial
  - The original work depicts information on the purchase intent rate and percentage change over from the previous year but       fails to make an impact on the claim
  - The claim has been proved with very minimal data, like two-year comparison. It is necessary to make a comparison over the     years to know the actual scenario as any consumer would tend to change or upgrade their devices only after 3-5 years from     the purchase date
  - Actual sales of the products in the surveyed years is not factored in this chart, which is an important metric to be           considered for the market analysis

## Redesign Goal
The goal of the redesign project is to develop a visulization which is persuasive and is capable of providing an insight on the claim in a better way when compared to the original work. 

The target audience of the visualization are technology giants(product manufacturers) like apple, samsung, google devices, etc. With this visualization the targeted audience will get a clear picture on the consumer buying trends and their purchase intent rate of theit products. With this information, they can forecast the live trend of the products and plan accordingly on their product inventions.

The redesigned visualization will refute the original claim that consumers are bored. Also, to make the claim stronger the important metrics purchase intent rate and actual sales of the products are taken into consideration.

## Data Wrangling
The data obtained from the orginial work had information on purchase intent rate over the years 2015 and 2016, which was clean and tidy. Hence the data did not require any wrangling activities. 

## Visualization Redesign

The first step of the visualization redesign was to check on the behaviour of the purchase intent rate across the products for the years 2015 and 2016. In tableau, with the help of the calculative field option created the change in purchase intent rate. When a graph was plotted across the purchase intent rate and the products. Then to add value to the claim that consumers are bored, developed a chart with the change in purchase intent rate for years 2015 and 2016.

![Alt text](https://github.com/nrajeswaran/Fall17_DataViz/blob/master/Redesign_Project/version3.png)

From the dashboard its clear that the change in purchase intent rate doesnot alone deplict the consumer behaviour. When analysed with the purchase intent rate of the individual years, we get a clear picture that the products with a negative change in purchase intent rate do not imply that the conumers are not interested in buying the products.

The products with a purchase intent rate greater than 30% are those which have made their show in the market and the ones with lower purchase intent rate are emerging their way into technolgy markets. Also when you compare the purchase intent rate in the years 2015 and 2016, the products which have a negative change does not imply that consumers are bored but rather represents the fact that the market can fluctuate 5-10% which is a common scenario.

The important metric to prove the claim that the consumers are not bored with the technology is to compare the purchase intent rate with the actaul sales data. To get the sales data, a calculative field was created in tableau. The graph below was then plotted comparing the actual sales to the purchase intent rate for different products.

![Alt text](https://github.com/nrajeswaran/Fall17_DataViz/blob/master/Redesign_Project/Finalversion.png)

The blue curve represents the actual sales of the product and the orange curve represents the change in purchase intent rate in the years 2015 and 2016. The products at the top of the blue curve depicts that they have large sales numbers when compared to the products in the bootom of the curve. When the products at the top of the blue curve is compared with the bottom of the curve, implies that the change in purchase intent rate of a product does not impact the sales of the particluar product. From this it is clear that when you check only the orange curve it deceives that the consumers are bored of buying products. But when compared with the metric- actual sales it refutes the claim that consumer are bored.

## Conclusion

The redesigned visualization is crisp on the information it provides and speaks the claim that consumers are interested with the technology growth and willing to buy cool products which delights the customers with new experiences. Even though Amazon failed to make an impact with its Firephone when it was launced in 2013, in the consecutive year one of their voice controlled smart home device popularly known as Echo with Alexa skills has emerged out to be one of the most successful consumer electronic products in the smart home market category. Thus, clarifies the fact that consumers are not bored of technology.

This visualization can be better improved by including metric on consumer buying trends. With this information the targeted audience(technology product manufacturers) will get better insight on how market varies according to the consumer trends.

## Reference

http://uk.businessinsider.com/people-are-getting-tired-of-buying-new-devices-2016-1
https://public.tableau.com/profile/rami3355#!/vizhome/AreConsumersBoredWithTechnology_3/Dashboard1



