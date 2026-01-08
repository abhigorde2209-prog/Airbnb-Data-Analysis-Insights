Airbnb data analysis and insights
Project description
This repository contains an end‑to‑end exploratory data analysis (EDA) of Airbnb listings. It focuses on understanding how room type, price, location, availability, and reviews influence demand and revenue. The project delivers clean visuals, concise insights, and actionable recommendations for hosts and platforms.
Dataset information
- Source: Public Airbnb listings dataset (CSV)
- Typical fields:
- Identifiers: id, name, host_id
- Location: neighbourhood, neighbourhood_group, latitude, longitude
- Listing: room_type, minimum_nights
- Demand: number_of_reviews, reviews_per_month
- Supply: availability_365
- Pricing: price
- Notes: Ensure columns exist or adapt the notebook to your dataset schema.


Key features
• 	Clean EDA workflow: Data loading, cleaning, feature checks, and visual analysis.
• 	Business‑ready visuals: Clear, labeled charts with concise takeaways.
• 	Actionable insights: Pricing, availability, and location strategies from observed patterns.
• 	Modular code: Reusable plotting functions and configurable paths.

Business insights
• 	Availability drives demand: Listings open most of the year receive more reviews and consistent engagement.
• 	Price vs engagement: Lower‑priced listings tend to attract more frequent reviews; premium listings trade volume for value.
• 	Room type matters: Entire homes/apartments are priced highest; private rooms capture budget demand with strong review activity.
• 	Location signals: Popular neighbourhood groups (e.g., central areas) show higher review counts and visibility.

Visualizations

1.	Distribution and trends
• 	Price distribution and outliers
• 	Reviews per month distribution

2.	Demand drivers
• 	Average reviews by room type (bar plot)
• 	Availability vs number of reviews (scatter)
• 	Price vs availability categories (box plot)
• 	Average reviews by availability category (bar plot)

3.  Pricing insights
• 	Room type vs price (box plot)
• 	Neighbourhood group vs price (box plot)

4.	Location
• 	Neighbourhood group vs average reviews (bar plot)

5.	Relationships
• 	Correlation heatmap (numeric features)
• 	Pair plot (price, reviews, availability)

Conclusion

The analysis shows clear, practical levers for improving performance: maintain higher availability, price competitively for your segment, focus on
room type positioning, and leverage high‑demand locations. These findings support host coaching, demand forecasting, and pricing optimization.

