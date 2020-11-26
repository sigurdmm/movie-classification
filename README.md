IMDB Movie Classifier
===

## Quick start

We use some syntax from Python version 3.7 and higher.

Ensure any necessary dependencies is installed:

1. pandas
1. numpy
1. sklearn
1. matplotlib

### Run classifications

The complete code generating and benchmarking of classifications are done in `movie_rating_predictor.ipynb`.

**Gotcha:** GridSearchCV can take up to 50 minutes for kNN and 30 minutes for Decision Tree.

### Generate Popular actors (should be present already)

Popular actors are generated in `generate_popular_actors.ipynb`, with the output being placed in `./generated/oscar/` (this should already exist).