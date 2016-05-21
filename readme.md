# 1st D3 Workshop at Slalom SF

The datasets available for this workshop are:
* [Wheat](https://github.com/rcrocker13/Slalom-SF-D3-Workshop-v0.0.0/blob/master/data/Wheat.csv)
* [Trees](https://github.com/rcrocker13/Slalom-SF-D3-Workshop-v0.0.0/blob/master/data/trees.csv)
* [Motor Trend Cars](https://github.com/rcrocker13/Slalom-SF-D3-Workshop-v0.0.0/blob/master/data/mtcars.csv)
* [Minard Temp](https://github.com/rcrocker13/Slalom-SF-D3-Workshop-v0.0.0/blob/master/data/Minard.temp.csv)
* [Iris](https://github.com/rcrocker13/Slalom-SF-D3-Workshop-v0.0.0/blob/master/data/iris.csv)
* [Ice Cream](https://github.com/rcrocker13/Slalom-SF-D3-Workshop-v0.0.0/blob/master/data/Icecream.csv)
* [Education](https://github.com/rcrocker13/Slalom-SF-D3-Workshop-v0.0.0/blob/master/data/education.csv)
* [Delivery](https://github.com/rcrocker13/Slalom-SF-D3-Workshop-v0.0.0/blob/master/data/delivery.csv)

See the brief summaries of each dataset below to try before you buy.

## Delivery
Delivery Time Data, from Montgomery and Peck (1982). The aim is to explain the time required to service a vending machine (Y) by means of the number of products stocked (X1) and the distance walked by the route driver (X2).

This dataset represent parcel delivery data with columns:
- n_prod:number of products being delivered
  - Most deliveries are about 7 packages. The minimum delivery in this dataset was of 2 packages and the most was of 30 packages.
- distance - distance walked by the route driver
  - The distance walked by most delivery men was 150 meters. The closets deliviers in this set were 36 meters with the maximum at 1,460. Walking 1,460 meters is the same as walking is nearly a mile.
- delTime - time to make the delivery
  - With the way this data is currently set up, there is little redundancy in exact delivery times. By setting delivery time on the x-axis for each of the deliveries we can see that most deliveries take about 18 minutes. There are a few outlier of delivers taking 40, 52 and 79 minutes.

##Education
Education Expenditure Data, from Chatterjee and Price (1977, p.108). This data set, representing the education expenditure variables in the 50 US states, providing an interesting example of heteroscedasticity.

If you, like me, don't know what heteroscedacity is let me save you the Google search...
> Heteroscedasticity is a hard word to pronounce, but it doesn't need to be a difficult concept to understand. Put simply, heteroscedasticity (also spelled heteroskedasticity) refers to the circumstance in which the variability of a variable is unequal across the range of values of a second variable that predicts it.

In the context of this data set we heteroscedasticity can likely shows up in each input (x variable) variable having a different outcome (y variable) depending on the state.

This dataset represent parcel delivery data with columns:
- State
  - Each state is represented once in this dataset.
- Region: Region (1=Northeastern, 2=North central, 3=Southern, 4=Western)
  - The most represented region is this dataset is 3 (Southern). The least represented region in the dataset of 1 (Northeastern).
- X1: Number of residents per thousand residing in urban areas in 1970
  - There's a wide reange of residents per 1000, but most value in this measure fall between 550 and 775.
- X2: Per capita personal income in 1973
  - This value is also a wide range but 50% of values can be found between 4.1 and 5.2.
- X3: Number of residents per thousand under 18 years of age in 1974
  - The range of values for this variable is a bit tighter. The minimum is 287 per 1000 and the maximum being 386 per 1000. Note that the maximum is actually considered an outlier. I wonder if it's an outliear among the other states in its region...
- Y: Per capita expenditure on public education in a state, projected for 1975
  - This bulk of the value for this variable are between $240 and $320. There's one extreme outlier of $546 begging to be explored.