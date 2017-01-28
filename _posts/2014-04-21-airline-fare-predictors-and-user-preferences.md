---
layout: post
published: true
author: robert barretto
description: fare predictors should be tailored for the user.
---

[Kaiser Fung has a great article](http://fivethirtyeight.com/features/when-to-hold-out-for-a-lower-airfare/?utm_source=digg&utm_medium=email) on using Big Data to predict airfare prices. He gives a great overview of Bing (Farecast) and Kayak regarding how they try to provide value for their users.

So here are a few of this conclusions:
1. There is quite a bit of spread in the eventual savings you get using a fare predictor.
2. When Kayak says to buy, it's usually the best you can do as prices indeed rise days after. This is good.
3. When Kayak says to wait, you might not actually see the price drop in subsequent days. This is bad.

One might wonder, why might this be?  And the answer has to do with what the customer wants.
A customer may want to be certain about a Kayak buy signal (high true positive rate), and usually doesn't track prices after buying, so he tolerates erroneous buy signals (high false positive rate). What the customer absolutely doesn't want to see is a Kayak wait signal, when in fact fares are rising on subsequent days.  So Kayak tries to maximize true positive rate and minimize false negative rates. Hence they optimize sensitivity.

On Bing (Farecast), they try to minimize the number of buy signals based on giving the impression that whenever a buy signal is present it is very meaningful (high true positive rate and low false positive rate). Hence they optimize precision (or positive predictive value). 

And at the end of the day, all of this has to do with the perceived value to the customer. A conservative customer may choose for better precision or sensitivity.  Maybe the ultimate solution would be to let the user decide with a slider bar....


