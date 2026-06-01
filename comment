# Eurovision Song Contest Data Analysis

## count_participations

Since the number of participating countries varies from year to year, I normalized the achieved ranking by relating each country's final placement to the total number of participants in that specific year. This allows for a fair comparison across different Eurovision editions.

## feature_importance

To determine the influence of various factors on a country's final ranking, I selected the following features:

### Numerical Features

- Points received
- Running order (starting position)
- Home advantage (0 = no, 1 = yes)

### Categorical Features

- Genre
- Song language

The categorical features were converted into dummy variables to avoid introducing an artificial ranking between categories. For example:

- `Language_German = 1` → The song is performed in German
- `Language_German = 0` → The song is not performed in German

### Target Variable

- Final ranking (placement)

## genre_influence

One of the most interesting questions was whether a particular genre stands out and which genre has the highest probability of winning.

The results not only reveal which genres tend to perform best, but also illustrate how popular genres have evolved throughout Eurovision history. Additionally, the analysis reflects the fact that no Eurovision Song Contest was held in 2020 due to the COVID-19 pandemic.

## prediction_2027

To create a more reliable prediction model based on historical data, countries with only a small number of participations had to be excluded.

My first approach was to include only countries with at least 30 participations. However, this still included countries that had not participated in recent years.

Therefore, I decided to only consider countries that had participated in at least one of the last three Eurovision Song Contests. This resulted in a significantly more realistic and satisfactory prediction output.

## Additional Material

All Jupyter Notebooks are attached as PDF files in German. The generated results and visualizations are provided as image files.
