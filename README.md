# Model price of Airbnb Boston

### Blog post: https://medium.com/@chencheninee/use-data-science-to-see-the-price-of-airbnb-83e592809d1f
### Motivation

Find out what would the factors that effect the price of Airbnb
using data from Airbnb Boston, available from Kaggle.com.


### File Descriptions

The files in the boston-airbnb-open-data folders are .csv files of data from Airbnb. There is also an ipython notebook of data analysis, exploration, and presentation.


### Libraries

Libraries necessary to run all cells in the Jupyter Notebook are as follows:
- Counter
- pandas
- numpy
- matplotlib
- LinearRegression
- seaborn
- sklearn.metrics


### Summary of Results

- According to our model, every additional bedroom you want to rent will change you additional 35 dollars, while each additional bathroom will cost 11 dollars extra.
- And each additional bed is just 3 dollars extra, and each additional accomodation and guest included costs 6. That means if you wanna bring more freinds, it won't cost you a lot. AirBnb is very cost-efficient.
- About the reviews we can see that no matter is the ratings or the number of reviews almost won't effect the price. This is surprisingly.
- As my thinking, more amenities is always better: every additional amenity available at a location will theoretically be a big plus for people who actually want it and a not-negative for those who don't. Hence on an individual level there's an incentive for a host to list irons, hot tubs, kitchens, the works. However, what a host chooses to list as an amenity is a signal about the "class" of the listing. If you put something "necessary" like "hangers" in your list maybe mean that you don't have something else necessary like hangers. So it will lead to a lower price.
- We see that neighborhood does indeed have a strong effect on the price of a listing. Far from the city center neighborhoods cost 40 dollars or less than average to rent in. Also, 40 dollars a night over the average seems like the premium you pay to live in a nice location.
