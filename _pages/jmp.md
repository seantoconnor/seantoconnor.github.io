---
layout: archive
title: "Job Market Paper"
permalink: /jmp/
author_profile: true
---
# Climate Adaptation in Non-Market Activities: The North-South Gap

This research examines the role of non-market behavioral adaptation to climate change in the United States with a novel estimation procedure that accounts for both short-run weather and long-run climate adjustments. First, I comprehensively review the temperature sensitivity of all activities in the American Time Use Survey using a ﬂexible non-linear estimation procedure. Most activities are found to be unresponsive to temperature with the exception of those that take place outdoors. These sensitive outdoor activities are studied further using the Climate Adaptation Response Estimation approach, which allows for temperature responses to vary geographically. The sensitivity to temperature varies across the country, and this variation is especially pronounced for cold-weather cities in which inhabitants reduce their outdoor and physical activities at extreme temperatures relative to warm-weather cities. Finally I forecast the expected change in outdoor activity time using climate models compiled by the Intergovernmental Panel on Climate Change, ﬁnding a large increase in outdoor time driven by warmer winters.

[Download here](http://seantoconnor.github.io/files/atus.pdf)

## The Great Outdoors

Lockdowns across the world in 2020 during the COVID-19 crisis have demonstrated the importance of spending time outdoors. Mental and physical health outcomes improve in natural environments. The figure below shows the share of time spent during different activities where the primary emotion was negative (e.g. a person felt more tired than alert or felt more depressed than happy):

![](http://seantoconnor.github.io/images/u_index.png)

Clearly the time spent outside is more pleasant during non-labor activities. Despite the importance of time outdoors, future climate change threatens the way people allocate time outside in ways that we don't understand. This research estimates communities' sensitivities to temperature and how these sensitivities vary across the United States due to the local climate.

To demonstrate the geographic heterogeneity in temperature sensitivity, the animation below plots the average share of the day spent outside in each state using data from the American Time Use Survey:
![](http://seantoconnor.github.io/images/facet.gif)

We see the expected seasonality -- people spend more time outside during the late spring and summer than in the winter -- but we also see some clear differences across states. What's driving this heterogeneity?

## The Sensitivity to Weather

Not all states are equally amenable to spending time outside. We wouldn't expect to be outdoors for long periods during a January in Chicago or a July in Phoenix. In order to assess the sensitivity to weather, I estimate a semi-parametric temperature response function for each metropolitan area in the country. Doing so gives us a better understanding of how people react to different ranges of temperatures.

The graph below plots the estimated coefficients for each 10-degree Farenheit temperature bin. The coefficients are relative to a baseline temperature of 60-70 degrees, so they can be interpreted as the change in the number of minutes spent outdoors each as a result of the day being in a particular temperature bin instead of the 60-70 degree bin. 

![](http://seantoconnor.github.io/images/care_stage1_alt.png)

The key takeaway is that most cities are very sensitive to cold temperatures and not very sensitive to hot temperatures. However, the effect is not uniform across all the cities in the sample. Importantly, these results estimate the short-run weather response, not the long-run climate response. In order to understand how the local climate influences the estimated temperature sensitivities, we need to go one step further.

## The Climate Forecast

![](http://seantoconnor.github.io/images/ipcc_scenarios.png)

![](http://seantoconnor.github.io/images/coef_sim.png)

## The Implications

![](http://seantoconnor.github.io/images/u_index_change.png)
