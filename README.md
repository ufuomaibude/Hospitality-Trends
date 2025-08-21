# Hospitality-Trends
Analyzing trends in the Hospitality industry; using Hotel Haven as a case study.

# Introduction
Hotel Haven is a luxury hotel chain with multiple locations. The hotel offers a wide range of services, including various types of rooms, meal plans, and parking options.
Hotel Haven has been facing challenges in predicting customer cancellations, which impacts their ability to manage resources effectively. The hotel wants to better understand their booking patterns and create strategies that could improve customer retention and reduce cancellations.

# Aim
The primary aim of this project is to design and implement a predictive model capable of forecasting hotel booking cancellations. By leveraging data-driven insights, the project seeks to empower the hotel with the ability to better manage resources, minimize revenue loss, and enhance customer retention through informed decision-making.


# Objectives
•	Analyze booking patterns to understand the underlying reasons behind customer cancellations.
•	Identify and evaluate key factors such as lead time, room type, market segment, and pricing that significantly influence booking status.
•	Develop and fine-tune a machine learning model to accurately predict booking outcomes.
•	Support hotel management in optimizing operations and improving customer satisfaction by reducing unnecessary cancellations.

# Summary of Impact
The project delivered a reliable predictor of hotel booking cancellations that equips management to act before costly churn occurs. The best-performing Machine Learning model achieved approximately 91% accuracy on the held-out test set, consistently outperforming simpler baselines. Beyond raw performance, the analysis surfaced actionable drivers of cancellation such as lead time, average price, booking channel, reservation month, and special requests providing the hotel with concrete levers for pricing strategies, targeted customer retention efforts, and operational optimization. 

Firstly, the project provided insights into cancellation behaviour by revealing that long lead times, higher booking prices, online reservations, certain seasonal patterns, and additional special requests significantly increase cancellation likelihood. Secondly, it identified key influencing factors, with Lead Time, Average Price, Market Segment, Reservation Month, and Special Requests emerging as the most critical variables. Thirdly, through the development and evaluation of multiple models, the project achieved an accurate predictive system with the top performer reaching ~0.91 accuracy. 
Finally, the predictive insights enable the hotel to improve operations and customer satisfaction by reducing last-minute cancellations through proactive retention measures, optimized pricing, and better resource allocation





# Summary and Conclusion
The dataset shows that most bookings are made by two adults, with few involving children. are for short stays, typically 1-2 weekend nights and 2 weeknights, and the price distribution is right-skewed due to high outliers. Longer lead times are linked to higher cancellation rates, and boxplot analysis reveals outliers in features such as weekend nights and average prices, indicating atypical booking behaviors. Key factors influencing cancellations include longer lead times, higher prices, online bookings, seasonal trends, special requests, and shorter stays. Longer lead times and higher prices increase cancellations, while online bookings show higher cancellation rates. Special requests and shorter stays also contribute to cancellations, while longer stays tend to be more stable. The Random Forest model was the best at predicting cancellations with 91% accuracy. Important features influencing the model include lead time, average price, market segment type, reservation month, and special requests, while other features had a lesser impact.

# Recommendation
•	Lead Time & Price Optimization: Offer discounts for early cancellation fees to reduce cancellations. Develop pricing strategies that balance affordability and profitability.
•	Online Booking Enhancement: Make the online booking platform user-friendly and non-refundable once payment is made. Use targeted ads and offer discounts for early online bookings. 
•	Special Requests: Offer premium services for special request customers to encourage them to pay for additional services and reduce cancellations. 
•	Seasonal Promotions: Create attractive promotions during peak seasons, like summer holidays, with competitive pricing and incentives to boost bookings. Room Upgrades: Investigate why rooms 6, 1, and 2 have high cancellation rates.










