# predictive_book_rating_analysis_using_machine_learning

The predictive book rating analysis machine learning project aims to develop a model that forecasts
book ratings based on various features. Leverage a dataset of book attributes and user reviews, the
project employs advanced machine learning techniques to predict average ratings accurately. The
model's predictive capabilities provide valuable insights for readers enhancing the understanding of
factors influencing book ratings in the digital era. The methodology involves collecting a diverse
dataset encompassing book attributes such as genre, author, publication date, text reviews count,
language code, and others. Various regression algorithms like linear regression, lasso regression
and possibly advanced techniques like gradient boosting are applied to analyze and predict average
book ratings. Feature engineering and selection techniques will be employed to identify the most
influential attributes affecting book ratings. The study aims to ascertain which features significantly
contribute to higher or lower ratings, unveiling patterns or correlations within the dataset.
Evaluation metrics including mean squared error, R-squared, and possibly cross-validation
techniques will be used to assess the performance of the regression models. The most effective
models will be identified based on their predictive accuracy and generalizability. The findings from
this research could provide valuable insights into the factors driving book ratings, aiding authors
and publishers in enhancing book quality and targeting specific reader preferences. Moreover, it
contributes to the broader field of machine learning applications in the predictive analytics for
cultural products like books.

The Dataset :

![OIP (4)](https://github.com/user-attachments/assets/abf1fc7d-ab35-4baf-ad4a-33fc4b45913b)


The dataset provided is a curation of Goodreads books based on real user information. It is contained
in a csv file called books.csv and gives the following book's attributes:
bookID: A unique identification number for each book.

title: The name under which the book was published.

authors: The names of the authors of the book. Multiple authors are delimited by “/”.

average_rating: The average rating of the book received in total.

isbn: Another unique number to identify the book, known as the International Standard Book
Number.

isbn13: A 13-digit ISBN to identify the book, instead of the standard 11-digit ISBN.

language_code: Indicates the primary language of the book. For instance, “eng” is standard for
English.

num_pages: The number of pages the book contains.

ratings_count: The total number of ratings the book received.

text_reviews_count: The total number of written text reviews the book received.

publication_date: The date the book was published.

publisher: The name of the book publisher.

Genre: The genre that the book belongs to.

The dataset consists of 875 null values, which were hence eliminated.

SYSTEM DESIGN – BLOCK DIAGRAM

![Screenshot (26)](https://github.com/user-attachments/assets/0cba62eb-57de-4000-9e8e-5df405972ab5)

RESULTS
1) Linear Regression: RMSE (least, the better)-0.2561


R2 score-0.27741

Adjusted R2 (closest to 1, the better)-0.27731

2) Lasso Regression: RMSE (least, the better)-0.25392
   
R2 score-0.304

Adjusted R2 (closest to 1, the better)-0.30426

 3)Gradient Boosting Regression: RMSE (least, the better)-0.2484

R2 score-0.5034

Adjusted R2 (closest to 1, the better)

Visual comparison of the given value and the predicted values:

![Screenshot (41)](https://github.com/user-attachments/assets/58da018d-61b6-4bf0-8208-6df0beeb58b9)
