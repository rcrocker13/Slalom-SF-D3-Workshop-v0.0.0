## 1st D3 Workshop at Slalom SF

### HTML
- Adding structure with elements

### CSS
- Selectors
- Properties and Values

### JavaScript
- Hello Console
- Variables
- Arrays
- functions
- Comments

### SVG
- The SVG Element
- Simple Shapes
- Styling SVGs with CSS
- Layering and Drawing Order

### Setup
- Downloading
- Referencing
- Web Server

### Data
- generate elements

#### Binding Data
- Please make your selection
- Data wants to be held

### Drawing with Data
- Drawing divs

### The Power of Data

### Drawing SVGs
- Pretty Colors Ooo

## Make a Bar Chart

## Make a Scatter Plot

The datasets available for this workshop are:
* [Iris](https://github.com/rcrocker13/Slalom-SF-D3-Workshop-v0.0.0/blob/master/data/iris.csv)
* [Motor Trend Cars](https://github.com/rcrocker13/Slalom-SF-D3-Workshop-v0.0.0/blob/master/data/mtcars.csv)
* [Ice Cream](https://github.com/rcrocker13/Slalom-SF-D3-Workshop-v0.0.0/blob/master/data/Icecream.csv)

See the brief summaries of each dataset below to try before you buy.

###Iris
This famous (Fisher's or Anderson's) iris data set gives the measurements in centimeters of the variables sepal length and width and petal length and width, respectively, for 50 flowers from each of 3 species of iris. The species are Iris setosa, versicolor, and virginica.

![Multi-plot of Iris dataset](https://github.com/rcrocker13/Slalom-SF-D3-Workshop-v0.0.0/blob/master/images/iris.png?raw=true)

Each arrow above is a variable of our data set.

The columns of this dataset are:
- Sepal_Length
  - Length maxes/mins out out 7.9/4.3 respectively.
- Sepal_Width
  - Width has a very normal looking distribution centered around 3 with one outlier of 4.4.
- Petal_Length
  - This variable is very interesting with its bi-modal distribution. The smaller-value concentration is much tighter, while the higher-value distribution is spread out.
- Petal_Width
  - Pedal width distribution has a similar behaviour as petal width.
- Species
  - In this dataset we have 50 observations of each species: setosa, versicolor and viginica.

###Motor Trend Cars
The data was extracted from the 1974 Motor Trend US magazine, and comprises fuel consumption and 10 aspects of automobile design and performance for 32 automobiles (1973–74 models).

![Motor Trend Cars](https://github.com/rcrocker13/Slalom-SF-D3-Workshop-v0.0.0/blob/master/images/motor-trend-cars.png?raw=true)

The columns of this dataset are:
- id: car name
  - This dataset looks at 32 individual vehicles.
- mpg: miles per gallon
  - The distribution is sparse, but the median in 1974 was just under 20 for this dataset.
- cyl: number of cylindars
  - We look at cars with 4, 6, and 8 cylindars. Most of the cars in this dataset are 8 cylindars.
- hp: gross horse power
  - Most of the cars cluster around lower horse power values. But there is one ride with exceptionally high hp. Does is have the lowest quarter second time?
- drat: the number of time the small gear at the end of the drive shaft must rotate in order to rotate the rear axel once
  - This gear ratio has a surprisingly wide distribution. Expore the relationships to understand the dynamics of this relationship.
- wt: weight in thousands
  - The distribution of this variable is also wide with a few clusters and centers above 3 thousand pounds. Cars today have shed a bit of weight.
- qsec: quarter mile time
  - These values vary by fractions of a second. See if you can't find out with variables contribute most to a low qsec time.
- vs: V/S
  - I can't tell you what this variable means, but I can tell the that 0's tend to be larger vehicles. You may what to use this field as a filter.
- am: automatic or manual transimission (0 = automatic, 1 = manual)
  - This is another binary variable. Our dataset has a few more automatics than manuals.
- gear: number of forward gears
  - This dataset contains forward gears of 3, 4, and 5. 5 is by far the least popular.
- carb: number of carborators
  - Most cars has either 2 or 4 carborators, but there are two beasts with 6 and 8 carbs.

###Ice Cream
Ice cream consumption was measured over 30 four-week periods from March 18, 1951 to July 11, 1953. The purpose of the study was to determine if ice cream consumption depends on the variables price, income, or temperature.

![Ice Crea](https://github.com/rcrocker13/Slalom-SF-D3-Workshop-v0.0.0/blob/master/images/ice-cream-love.png?raw=true)

The columns of this dataset are:
- cons: Ice cream consumption in pints per capita
  - We have a sparse distribution with only 30 observations. However we can see the a 1/3 of a pint is a popular value.
- income: Weekly family income in dollars
  - Not exactly a representative sample of income, but well spread.
- price: Price of ice cream per pint in dollars
  - It looks like the quarter was a popular amount barter mechanism for ice cream trade back in the day.
- temp: Mean temperature in degrees F
  - This was not a warm climate where ice cream consuption was observed.
