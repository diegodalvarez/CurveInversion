# Curve Inversion
Original work inspired from Stephanie Lo and Roni Israelov at NDVR in their work called What Does an Inverted Yield Curve Mean for Upcoming Interest Rate Movements? [link here](https://ndvr.com/journal/what-does-an-inverted-yield-curve-mean)

The question at hand is what are the results of yield curve inversion. Although negative term premia may occur the authors suggest that its the shorter end of the curve inverting while the longer end of the curve stays relatively the same.
Start by looking at the distribution that comes from curve inversion
![image](https://github.com/diegodalvarez/CurveInversion/assets/48641554/678e6dd7-804b-47f3-a579-8e86ea1384e3)

We can examine how yield curve changes adjust in the future. The regression below shows that yield curve inversion usually revert to normality. In this case I've extended the scenarios to include a 3m bill and 10y yield curve measure since it is also a commonly used measurement. 
![image](https://github.com/diegodalvarez/CurveInversion/assets/48641554/49683921-7fc0-45f0-b17a-972db2e17f89)

Now that its been established that curve inversion usually leads to normality we can examine the drivers of curve inversion. The regression below runs both scenarios and by looking at the blue line we can see that the main driver of yield curve inversion is from the shorter end of the curve. 
![image](https://github.com/diegodalvarez/CurveInversion/assets/48641554/e597e3f6-156b-4fd9-a89a-b72378c0adf2)
