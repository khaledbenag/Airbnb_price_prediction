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

#!/bin/bash

#File: tree-md

tree=$(tree -tf --noreport -I '*~' --charset ascii $1 |
       sed -e 's/| \+/  /g' -e 's/[|`]-\+/ */g' -e 's:\(* \)\(\(.*/\)\([^/]\+\)\):\1[\4](\2):g')

printf "# Project tree\n\n${tree}"

# References
* Seattle data: https://www.kaggle.com/airbnb/seattle/data
* Boston data: https://www.kaggle.com/airbnb/boston
