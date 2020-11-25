Project Name: [The Prediction of Airbnb Price in NYC: the effect of COVID-19 in the Airbnb market](https://github.com/noriolg/ORIE4741_project)

Group Members: Sophie Zhao(sbz24), Linna Yue(ly389), Nicolás Oriol Guerra(no227)

The housing market has been a rising problem due to the steady increase of housing costs during the past decade. The problem of affordable housing is present in many cities in both America and Europe and it has also made its way to the front seat of political debate in recent years. However, after the Covid-19 pandemic, some reports indicate that housing prices are decreasing and that the trend may be reversed in the coming months.

The aim of this project is to understand what factors may affect housing prices and how those factors have been altered by the pandemic. In order to do so, a database of Airbnb listings will be used comparing the same city at different points in time (pre and post pandemic). Some questions that could help to investigate the problem are: Can we predict Airbnb prices before and after Covid-19?  Is the model the same or have the factors changed importance? Have popular housing locations changed in that time? Answering this problem could be important to identify underlying trends in renting which could be applied as a benchmark to the more general housing market. It could also point out important relationships between the different variables and how they affect price and provide a narrow overview of the effect that Covid-19 has had on the economy.


A brief overview of the files present in the project is provided:

* `Data Mining and Cleaning` takes initial airbnb data from `data/initial data/` and cleans it whilst doing the necessary feature transformations
* `EDA` several plots are produced to better understant the data distribution
* `Airbnb Map NYC` maps the location of each of the Airbnb's to produce a visual representation over the city's map
* `Model development` computes the first steps towards building a regression model. The best approach towards the final model is obtained here
* `Airbnb Model` develops the final model in depth providing the necessary explanations and delving deeper into the results than in the `Model development` file