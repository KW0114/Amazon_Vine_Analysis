# Amazon Vine Analysis

## Overview

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. This project compares reviews from Vine members vs. non-members in terms of number and % of 5 star reviews.

## Results

For my project, I chose reviews on video games for my dataset.

The table below shows some key statistics from a cleaned dataset:

![screenshot](https://github.com/KW0114/Amazon_Vine_Analysis/blob/9d82552678a24e96be823f626765b7935ea8f563/Analysis_Screenshot.png)


* There are 94 reviews from Vine members, and 40471 reviews from non-members - looks like not many Vine members review video games.
* There are 48 5-star reviews from Vine members, which makes up 51.1% of their reviews.
* There are 15663 5-star reviews from non-members, which makes up 38.7% of their reviews.


## Summary

There definitely does seem to be a bias in the Vine reviews, as there are almost 15% more 5-star reviews among those customers.
The main downside, however, is the extremely small amount of reviews from Vine members in my dataset. In order to make a more informed
claim about the bias, it would help for there to be a more even split between members and non-members. However, since Vine members
are paid to write their reviews, they definitely have an incentive to inflate their star rating.

Perhaps one other detial we could take into account in our analysis is whether or not the purchased is verified. This could possibly
weed out extremely low reviews that could be bringing the % down for the non-members.
