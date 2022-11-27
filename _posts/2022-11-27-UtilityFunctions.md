---
date: 2022-11-27
title: Utility Functions
---
Utility functions offer a way to quantify how much value you get form a certain ammount of a given activity. 

## Generic linear utility function

The generic linear utility funcion gives you a highly flexible way to define the utility of your activities. It forms a utility function by binding together different point that the user specifies. This is illustrated in the following figure: 

![image](https://user-images.githubusercontent.com/44125052/204153528-cada2b6b-0629-4dc1-ab60-3d8e0f3ed8c9.png)

Note that the utility function binds together all the specified points. Also note that the tility function continues in both directions beyond the specified points. 

![image](https://user-images.githubusercontent.com/44125052/204153546-d552234b-a37f-4b6d-bca9-89248075702e.png)

You can give the generic linear utility function as many points as you want. This allows the user to create a huge set of utility funcitons. 

## Normal CDF utility function

Normal CDF utility function only requires one poit to specify:

![image](https://user-images.githubusercontent.com/44125052/204153621-f1f922e4-0517-468f-b263-a4efa22ee763.png)

It is less flexible in its shape, but provides a very smooth utility increase compared to the generic linear utility funcion 

![image](https://user-images.githubusercontent.com/44125052/204153601-8919ef50-30a3-4d2c-af12-d8481e84233d.png)

This utility funciton is appropriate for most activities that follow a [diminishing return](https://en.wikipedia.org/wiki/Diminishing_returns) structure.
