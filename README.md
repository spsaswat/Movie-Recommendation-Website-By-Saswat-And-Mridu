# Moviely


Moviely is a Web based Movie Recommendation System.
It uses Machine Learning Recommendation system Algorithm, Collaborative Filtering using Matrix Factoization Algorithm to recommend movies to users based on the previous users ratings.

New users are recommended movies as per some pre defined rule.
Also new users can rate the movies available and their responses will further contribute to the recommendation to other users.


### Tools and Technologies used
     
<ul>
     <li>Django Framework</li>
     <li>HTML5</li>
     <li>CSS</li>
     <li>Bootstrap</li>
     <li>SQLite3</li>
</ul>

### Quick Start Guide

Clone the repository

```bash
# Change Directory
$ cd Moviely

# Create Virtual Environment(LINUX)
$ virtualenv venv
$ source venv/bin/activate

# Install dependencies
$ pip install requirements.txt

# Migrate database files
$ python manage.py migrate

# launch ...
$ python manage.py runserver

```
