# MoviesLikeCLI

MoviesLike is both a command line and web application. It's purpose is to the solve two problems.

1. Allow users to query for a single movie and receive a list of similar films.
2. Recommend movies based on the users previous ratings.

## Dependencies

1. Python
2. MySQL
3. Docker

## How does it work?

MoviesLike uses a python interface to scrape movie data from IMDB given a specified criteria.

The interface scrapes IMDB for the {movie data} - {title, outline, credit, genre}, converts the data to CSV and stores it in a MYSQL database for future queries.

Each new setup of the CLI requires MYSQL?

## Getting Started
