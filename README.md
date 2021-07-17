# Exploratory Data Analysis

You have the data for the 100 top-rated movies from the past decade along with various pieces of information about the movie, its actors, and the voters who have rated these movies online. In this assignment, you will try to find some interesting insights into these movies and their voters, using Python.

## Profit Analysis

 * Creating a new column called profit which contains the difference of the two columns: gross and budget.
 * Sorting the dataframe using the profit column as reference.
 * Extracting the top ten profiting movies in descending order and store them in a new dataframe - top10.
 
 * Plotting a scatter or a joint plot between the columns budget and profit and write a few words on what you observed.

![Capture1](https://user-images.githubusercontent.com/85448559/126030081-77022365-22e5-482d-9d6a-7392fdef7b19.JPG)

 * We observed from the Scatter Plot,

  * That the average profits of all the movies are in the range of 0-200 Million$.
  * Some of the movies that are in the negative profit zone doesn't mean that they are performing bad but they might be performing good outside USA. We can manually check their Gross profit worldwide and conclude.

## Runtime Analysis

 * There is a column named Runtime in the dataframe which primarily shows the length of the movie. It might be intersting to see how this variable this distributed. 
 * Plotting a histogram or distplot of seaborn to find the Runtime range most of the movies fall into.

![Capture2](https://user-images.githubusercontent.com/85448559/126030133-3df6b46d-335f-4137-8255-5759f35d5c6e.JPG)

 * We can observe that Runtime of movies is around 120 mins.

## Demographic Analysis

![Capture3](https://user-images.githubusercontent.com/85448559/126030205-cb118edb-ecba-4112-8dba-27cbc4f80ba8.JPG)

 * From the Bar chart, we can observe that directors are more inclined towards __Drama__ genre than other, second being the __Adventure__ genre.

## Gender and Genre

![Capture4](https://user-images.githubusercontent.com/85448559/126030299-4a5a852a-5e84-4b31-be26-d1bbb085b7b1.JPG)

 * Sci-Fi appears to be the highest rated genre in the age group of U18 for both males and females. Also, females in this age group have rated it a bit higher than the males in the same age group. What more can you infer from the two heatmaps that you have plotted? Write your three inferences/observations below:

    * Inference 1: Age ranging 45 & Above have given lower votes irrespective of the gender.
    * Inference 2: Animation genre is being loved pretty much by the Female group when compared with the counterpart.
    * Inference 3: Male aged between 18-29 loved watching the movies compared to the Female counterpart.

## Top Genre's

![Capture5](https://user-images.githubusercontent.com/85448559/126030359-5aa26f11-04e3-4138-92d4-9a69cb810c0f.JPG)

 * The Thriller & Sci-Fi genre is being voted least by the top 1000 voters.
 * Action & Adventure genre is being loved by a max. chunk of people among the top 1000 voters.







