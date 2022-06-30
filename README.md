# Bike-sharing-demand-prediction

![image1_hH9B4gs](https://user-images.githubusercontent.com/84036652/176590844-b4e6a903-b102-4dfe-9250-412e086e1a3d.jpg)

Now a days people are traveling more from one place to another. Day by day the fuel prices are
growing and touching to the sky. People started to find the cheap transportation services. There
are several other transportation services are available in this era but people do not want to waste
their time on those services. But they want a fast and cheaper solution over these
services. Basically, if you are living in metro cities, then it can be quite complicated for you to
handle the travelling expenses. No doubt, people have their private vehicles such as car and
motorbike, but this might not be cost-efficient for short distances.

Therefore, the question is how we can save money? So, the answer is to ride the bike which is very
efficient in every term like in fuel, pollution, etc. There are lots of bike rental services available all
over the world in which people can easily choose in order to go anywhere. The people who
recently settled in metro cities can experience the rental bike services in their area.
You don’t need to pay for public transportation and it can save your many other expenses.
Therefore, you can easily save the desired amount of money to spend on something better such as
eating dinner. Not only this, it is really easy to ride the bike that you have rented so this would be
really supportive for you. And because of riding the bike everyone’s body will remain healthy and
there is no need to see a doctor once in a while.

Bike rental systems are great for the environment. Obviously, bikes do not produce any emissions;
tourist visiting a new city won’t be contributing any pollution which they might have brought with
their cars. If they have their cars, they’ll drive around for their entire trip, causing more traffic and
extra pollution. Bike renting system provides option to experience the city on a bike, which
exciting, less expensive and more convenient way of travelling.

Therefore, to increase the use of bikes we analyzed the past dataset of rented bikes with the use of
various Machine Learning models.

Through this analysis we got to know that the highest number of bike rents occur in "summer"
while the least bike rents occur in "winter". In hourly basis, the bike counts increase in the
afternoon (from 3pm to 8pm). There are two times increase in bike count occurrences, at 7am and
at 5pm, which is most likely to be caused by workers going to office in the morning and going back
home in the afternoon.

From analysis, we saw that in general the number of bike rents in 2018 was more than in 2017. The
bike counts peak in the afternoon (from 3pm to 8pm) where temperature is the highest, with the
most visibility, windspeed, and least humidity.

Based on this analysis, we built a Random Forest model to predict the number of bike rents. Also,
we used various other models like Linear Regression, Decision Trees but in this model, we couldn’t
get much scores. So that finally we went to Random Forest model.

We made new features such as day, month and year derived from the dates. We achieved an R2
accuracy of 81% based on Random Forest algorithm.
Finally, it was found that rainfall, snowfall, every season and temperature is the most determining
weather predictors.

