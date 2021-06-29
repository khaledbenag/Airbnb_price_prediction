![plot](https://github.com/khaledbenag/Airbnb_price_prediction/blob/main/figures/seat_bost.png)

# Context
Airbnb is an online marketplace that connects people who want to rent out their homes with people looking for accommodation in that area. The firm has no ownership of the listings on the app; rather, it operates as a matchmaker and gets commissions on each booking. The company is founded in 2008, and it is based in San Francisco, California, USA.
Airbnb's data is a good place to start data exploration and explanation. In 2016, Murray Cox, an independent digital storyteller, fascinated by Airbnb data, launched an investigative site called Inside Airbnb, bringing back and viewing data from scraped listings on Airbnb.

In this notebook, I will focus only on listings data from Seattle and Boston. I will conduct a comparison study on both datasets to answer three business questions.
* Which city is most expensive?
* Which are the property type most hosted?
* Which are the most expensive and cheapest neighborhood in Seattle and Boston?

For more insights please check my blog: https://k-benaggoune.medium.com/python-for-airbnb-hosts-exploration-boston-vs-seattle-cf9ca2126954

# Requirements
* Python 3
* Jupyter notebook
* Pandas
* Seaborn
* os
* Matplotlib
* Numpy
* 
# Project tree:
   - [Airbnb.ipynb](Airbnb.ipynb)
   - [LICENSE](LICENSE)
   - [README.md](README.md)
   - [data](data)
     - [Boston](data/Boston)
       - [calendar.csv](data/Boston/calendar.csv)
       - [listings.csv](data/Boston/listings.csv)
       - [reviews.csv](data/Boston/reviews.csv)
     - [Seattle](data/Seattle)
       - [calendar.csv](data/Seatle/calendar.csv)
       - [listings.csv](data/Seatle/listings.csv)
       - [reviews.csv](data/Seatle/reviews.csv)
   - [figures](figures)

# Conclusion 

In this article, we explored Airbnb data from Seattle and Boston to understand three areas of interest: pricing, property type, and neighborhood impact. While we found useful information at each level, many questions remain, like which characteristics and their associated impact make each neighborhood different from the others. In addition, further inspection of the listings by seasonality could yield more information to accurately select the best features for the price prediction task.

For more information please check my blog: https://k-benaggoune.medium.com/python-for-airbnb-hosts-exploration-boston-vs-seattle-cf9ca2126954

# Acknowledgments
I would thank #Udacity for the data science advanced nanodegree program and Kaggle for providing the two datasets.
* Seattle data: https://www.kaggle.com/airbnb/seattle/data
* Boston data: https://www.kaggle.com/airbnb/boston
