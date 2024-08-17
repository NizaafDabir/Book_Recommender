# 📚 Book Recommender system

![download](https://github.com/user-attachments/assets/2a0a70f7-0742-42c1-8287-444ff28adbf7)


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> 📄 Introduction</h2>

In our increasingly digital age, the vast world of literature is at our fingertips. With millions of books available, finding the perfect read can be a daunting task. That's where book recommendation systems come into play, revolutionizing the way we discover and engage with books.This Recommendation System is built using Popularity Based and Collaborative Filitering Based recommendation system.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: Dataset </h2>

[![Kaggle Badge](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white)](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset)  ⬅️ Click here for the Dataset

Dataset used in this project is the Kaggle Book-Recommendation dataset.This Dataset has total 3 CSV files Users.csv ,Books.csv and  Ratings.csv  

**Users**

* User-ID: `A unique identification number for each user`
* Location: `It contains city,state and country  to which the user belongs ,separated by commas`
* Age: `The age of the user`

**Books**

* ISBN: `International Standard Book Number unique to each edition of the book`
* Book-Title: `Title of the book`
* Book-Author: `Author of the book(incase of several authors only the first is provided)`
* Year-of-Publication: `The year in which the particular edition of the book was published`
* Publisher: `Name of the Book Publishing company`
* Image-URL-S: `URL link to a small version of the book cover displayed on the Amazon website`
* Image-URL-M:	`URL link to Medium version image of the book cover displayed on the Amazon website`
* Image-URL-L: `URL link to Large sized image of the book cover displayed on the Amazon website`

**Ratings**

* User-ID: `A unique identification number for each user`
* ISBN: `International Standard Book Number unique to each edition of the book`
* Book-Rating: `The rating given by the user (identified by User-ID) for the book (identified by ISBN). It is either explicit,expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit,expressed by 0.`

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> 📑 Steps involved </h2>

* **Loading of Dataset in Jupyter Notebook**
* **Data Preprocessing**
* **Implementation of Recommender System approaches**
* **Pickling of Dataframes**
* **Creating Web Application using Flask**

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2>💻 Approaches used</h2>

**1. Popularity Based recommendation system :** A popularity-based recommender system, often referred to as a "popularity-based recommendation system" or "popularity recommender," is a straightforward approach to recommending items, such as books, to users based on their overall popularity or popularity within a specific group or demographic. It doesn't rely on personalized user data or preferences but instead suggests items that are already widely recognized or have gained popularity among a broad audience.Here the recommendation will be done for the most popular books which will have the highest ratings.The number of ratings will be calulated of all only those users who have done minimum 250 ratings on any books.

**2. Collaborative Filitering Based recommendation system :** Collaborative Filtering is a widely used approach in recommendation systems, including those for books. It relies on user behavior and interactions to make personalized book recommendations.There are two main types of collaborative filtering User-Based Collaborative Filtering & Item-Based Collaborative Filtering.This Recommendation sytem will recommend only those books on which the minimum book Ratings are 50 and the user has rated more than 200 times.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :bulb: Conclusion</h2>

* Harry Potter and the Prisoner of Azkaban (Book 3) by J. K. Rowling is most popular books with 428 votes.
* Next Four most popular books are of the same author J. K. Rowling with the same book name Harry Potter with different series of books.
* The Collaborative Filter Based Recommender will recommend the 5 books with minimum Book Ratings of 50 and the user rating more than 200 .

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :bulb: Reference</h2>

* Channel Name : CampusX
* Link to the Project : https://www.youtube.com/watch?v=1YoD0fg3_EM&t=987s

[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nizaaf-dabir-524596203/)
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NizaafDabir)
