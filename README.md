# Project Title: 
Revenue Optimization & Pricing Insights for Swift-Haul Ride Sharing Company 


## Business context: 
Ride-sharing businesses operate in constantly changing conditions driven by traffic, weather, and demand. This project analyzes whether the company’s pricing strategy effectively compensates for longer ride times and higher operational risks, while maintaining stable revenue performance across different conditions. The goal is to support fair pricing, revenue optimization, and better decision-making through data-driven insights.

Business Problems Solved: This project focused on answering key business questions, including:
1. Is the fare charged increasing proportionally with distance, or are there pricing inconsistencies that could cause customer complaints or revenue leakage?
2.Are longer ride durations resulting in adequately higher fares, or is the business losing money on time-heavy rides (traffic delays)?
3. Does surge pricing actually generate higher average revenue per ride, or is it being applied without meaningful financial impact?
4. Are promo codes significantly reducing average fare value, and are they being applied to rides that would have occurred anyway?
5. Which ride mode (Morning vs Night rides) generates higher revenue per kilometer, and are pricing strategies aligned accordingly?
6 When traffic level is high, does fare pricing sufficiently compensate for increased ride time, or is revenue per minute declining?
7.During adverse weather conditions, is pricing adjusted in a way that maintains revenue efficiency, or does revenue per ride drop?

Data Overview: The dataset contains ride-level operational data, including:

Ride ID
User ID	
Driver ID
Ride start date&time
Ride mode	
Pickup Location	
Dropoff Location	
Distance km	
Distance Km range	
Ride Category
Ride Duration	
Revenue per hour	
Ride end date&time	
Fare Amount	
Payment Method	
Ride Status	
User Rating	
Driver Rating	
Surge Pricing	
Promo Code Used	
Vehicle Type	
Weather Condition	
Traffic Level	
Driver Experience Years	
User Type	
Fare per Km
 


Methodology: The project followed a business-driven analytical approach. First, the dataset was reviewed to understand ride operations, pricing drivers, and revenue-related variables. The data was then cleaned and standardized to ensure accurate time, duration, and revenue calculations.
Next, key performance metrics such as revenue per hour were derived to measure pricing efficiency under different traffic and weather conditions. Aggregated analysis was conducted to identify patterns, risks, and revenue behavior across operational scenarios.
Finally, insights were translated into clear business interpretations and actionable recommendations, focusing on revenue sustainability, pricing effectiveness, and operational decision-making.



Key Insights:
1 There is a clear price inconsistence within the distance travelled by users per KM as short distance ride cost more compared to long distance ride on per KM basis indicating lack of fair pricing.

2 Fares for longer rides are charged preoperationally based on the number of KM traveled. Even at this, longer rides still lag greatly on revenue generated per hour considering time consumption and other input cost when been compared with short and medium ride. As this can be tied to more input cost on long rides or lagging pricing method.

3 Although price surge is applied on some ride, it adds only a fraction to average revenue generated per ride which stands at (₦0.46).

4 Rides without promotions generate a slightly higher average fare value than rides with promotions (₦60.21 vs ₦59.81), a difference of 0.67%. This indicates that while promotions support engagement, they may be slightly reducing per-ride revenue

5) Analysis of average revenue per kilometer shows that morning rides generate ₦3.65/km, while night rides generate ₦3.63/km. The marginal difference indicates that both ride modes contribute almost equally to revenue efficiency. This suggests that current pricing between morning and night rides is well balanced, and revenue growth is more likely to come from increasing ride volume or optimizing operational costs rather than adjusting mode-based pricing.

6) During high traffic congestion, average revenue per hour edge higher at #1,836.67 which surpasses revenue generated during low and medium traffic rides. This shows the business isn’t experiencing revenue loss as a result of extra time spent on high traffic rides.

7) Average revenue per hour is strategically moderated across different weather conditions to align with the present weather challenges and risk exposure the company might face.  Interworlds, fare amount moderate downwards during better weather conditions and experience an uptick during hash weather. Therefore revenue per hour can be said to be balanced across different weather.





Business Recommendations:

1 Adopt a pricing model that includes a base fare, consistent charges per kilometer, and adjustments based on ride duration. This ensures short trips cover basic operating costs while long-distance rides are priced fairly according to distance and time spent, leading to more balanced and sustainable revenue. 

2 Introduce a hybrid fare pricing model that dynamically balances distance (KM) and time spent, with a stronger weight on ride duration for longer trips. This ensures that extended ride times caused by traffic, road conditions, or long distances are adequately monetized, thereby improving revenue per hour and protecting driver and platform profitability on long rides.

3 Given the minimal impact of surge pricing on average revenue per ride, and instead of relying on surge pricing as a primary revenue lever, the business should prioritize revenue growth through ride volume expansion and cost efficiency. This includes increasing ride frequency, optimizing routes to reduce delays and fuel consumption, and accelerating new user acquisition to drive sustainable revenue growth.

4. Promotions should be strategically targeted rather than broadly applied, focusing on customer acquisition, reactivation (bringing back users), or low-demand periods instead of high-intent or peak rides. This ensures promotions drive incremental demand without unnecessarily reducing revenue from riders who would have paid full price.

5 Since revenue per kilometer is nearly identical between morning and night rides, the business should maintain the current time-based pricing structure and redirect strategic focus toward ride volume growth and cost optimization rather than price adjustments by ride mode.

6 The company should retain traffic-based pricing but focus on fine-tuning surge thresholds to ensure revenue per hour remains positive during congestion, while also avoiding excessive fare increases that could reduce ride demand or customer satisfaction.

7 Maintain the current weather-responsive pricing strategy, but enhance it with clearer weather-based pricing tiers and proactive rider communication. This will ensure continued revenue stability while improving customer trust and ride acceptance during adverse weather conditions.


Tools & Skills Used: 
Power query:(Data cleaning, separation of variables, converting raw number to time (ride duration), signing right data type, replacing values)

Excel (calculated columns, statistical aggregation, pivot tables, calculated metrics, data visualization& dashboard)



Value Delivered:

This project delivered clear, data-driven insights into how traffic congestion, weather conditions, and pricing strategies impact revenue efficiency in a ride-sharing business.
By shifting the analysis from total fare to revenue per hour, the project demonstrated that existing pricing mechanisms effectively compensate for longer ride durations caused by high traffic and adverse weather.
The analysis also highlighted how surge pricing and weather-adjusted fares help stabilize earnings, protect revenue during operational challenges, and support fair value exchange between riders, drivers, and the platform.
Overall, the project provides a practical framework for evaluating pricing effectiveness, identifying revenue risks, and supporting smarter pricing and operational decisions that improve profitability without compromising customer experience.

 







# Revenue-Optimization-And-Pricing-Insights-for-Swift-Haul-Ride-Sharing-Company-
