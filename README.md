This is my final project for NLP class.
I used different strategies for active learning on Imdb dataset, like random,uncertainty,diversity and...
at last i used bert pretrained model and then used that model uncertainty for sampling new labeled data for my main model

our main work is on the file named "(custom model)uncertainty of Bert"

data set is available here: https://ai.stanford.edu/~amaas/data/sentiment/

this is the result from using pretrained bert for getting uncertainty, then training the model on most uncertain data(each 15 epoch is a new cycle o factive leaning):
![e](https://github.com/mirmirmo/Active-learning-on-Imdb-dataset/assets/141586615/73d13b22-ab17-41c0-adc2-2e2eab6cbfaa)
