# About this program

As you can see in requirements.txt file, you need to install flask. to run this whole program.
You will see one python files, which is 'SI507_project3.py', and db file, 'sample_movies.db' which saved movie's and director's information.


### WHAT 'SI507_project3.py' CONTAINS
1. It has **flask** application which allow uers to go to the routes at the following paths.
2. There are total three routes.
  - http://127.0.0.1:5000/
    - *The user will see "Hello, I am going to show you a movie list. So far, we have 6 movies saved."*
  - http://127.0.0.1:5000/movie/new/**title/director/rating**
    - *As user puts movie title, director and rating in the url, they will be added to the database.*
    - *For example, if user put this 'http://127.0.0.1:5000/movie/new/Aquaman/James Wan/7.2' as a url, they will see "New movie: Aquaman by James Wan. Check out the URL for ALL movies to see the whole list." in the internet browser.
  - http://127.0.0.1:5000/all_movies
    - *The user will see all movies like below.*
      - Captain Marvel by Anna Boden - 7.1
      - Spider-man by Sam Raimi - 7.3
      - The Evil Dead by Sam Raimi - 7.5
      - Avengers: Infinity War by Anthony Russo - 8.5
      - Toy Story by John Lasseter - 8.3
      - La La Land by Damien Chazelle - 8


### HOW TO RUN (IN LOCAL COMPUTER)
* Open terminal or any command prompt you have.
* Make sure you have installed all in **requirements.txt** like flask.
* Type: python3 SI507_project3.py runserver
* Then, open Chrome or Safari and go to http://127.0.0.1:5000/
    *You will see 'Hello, I am going to show you a movie list. So far, we have 6 movies saved.' in the window.*
