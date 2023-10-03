# 📚 Book Recommender system
![download](https://github.com/NizaafDabir/Book_Recommender/assets/110449627/85a74513-4c46-43a7-8ec3-490d9beb0b0d)

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :floppy_disk: Table of Content</h2>

  * [Introduction](#Introduction)
  * [Dataset](#dataset)
  * [Steps involved](#Steps-involved)
  * [Approaches used](#Approaches-used)
  * [Conclusion](#Conclusion)

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> 📄 Introduction</h2>

In our increasingly digital age, the vast world of literature is at our fingertips. With millions of books available, finding the perfect read can be a daunting task. That's where book recommendation systems come into play, revolutionizing the way we discover and engage with books.This Recommendation System is built using Popularity Based and Collaborative Filitering Based recommendation system.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: Dataset </h2>

Dataset used in this project is the Kaggle Book-Recommendation dataset. [Kaggle Dataset](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset)
 
This Dataset has total 3 CSV files Users.csv ,Books.csv and  Ratings.csv  

**Users**

* User-ID: A unique identification number for each user
* Location:It contains city,state and country  to which the user belongs ,separated by commas
* Age:The age of the user

**Books**

* ISBN:International Standard Book Number unique to each edition of the book
* Book-Title:Title of the book
* Book-Author:Author of the book(incase of several authors only the first is provided)
* Year-of-Publication:The year in which the particular edition of the book was published
* Publisher:Name of the Book Publishing company
* Image-URL-S: URL link to a small version of the book cover displayed on the Amazon website
* Image-URL-M:	URL link to Medium version image of the book cover displayed on the Amazon website
* Image-URL-L: URL link to Large sized image of the book cover displayed on the Amazon website

**Ratings**

* User-ID:as mentioned above
* ISBN:as mentioned above
* Book-Rating: The rating given by the user (identified by User-ID) for the book (identified by ISBN). It is either explicit,expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit,expressed by 0.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> 📑 Steps involved </h2>

* **Loading of Dataset in Jupyter Notebook**
* **Data Preprocessing**
* **Implementation of Recommender System approaches**
* **Pickling of Dataframes**
* **Creating Web Application using Flask**

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

