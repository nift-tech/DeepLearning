# What is a Kalman Filter?

A Kalman Filter is an algorithm that takes data inputs from multiple sources and estimates unknown variables, despite a potentially high level of signal noise. Often used in navigation and control technology, the Kalman Filter has the advantage of being able to predict unknown values more accurately than if individual predictions are made using singular methods of measurement.

# How does a Kalman Filter work?

Kalman Filters use a two-step process for estimating unknown variables. The algorithm works by first estimating the current state variables, and measures their uncertainties. Then, the algorithm updates the estimates using a weighted average, wherein more weight is attributed to estimates with higher levels of uncertainty. Because the filter takes in information from multiple sources, both current state and predicted state, the filter is able to provide a level of accuracy higher than if estimates were made given only one of the multiple sources.


                                                                ###### Source

# Kalman Filter and Machine Learning

One of the most common uses for the Kalman Filter is in navigation and positioning technology. Imagine a car with a GPS transmitter is traveling down a mountain road. A Kalman Filter can be applied to take in the GPS data from the car, however GPS devices are not always entirely accurate. So, the Kalman Filter can take in speed and velocity data to adjust the rate of change in the cars position over time. Naturally, given the laws of physics, the level of variable uncertainty is lower when the car is traveling faster, and vice versa. All of this information is used to predict where the car will be, and then the process is repeated with updated information as the car travels down the road. Because the Kalman Filter is recursive, it doesn't need to know the entirety of the cars position and speed data, but rather just the last known position and speed. The underlying model of updating information is similar to that of a Hidden Markov model.



###### (https://deepai.org/machine-learning-glossary-and-terms/kalman-filter)
