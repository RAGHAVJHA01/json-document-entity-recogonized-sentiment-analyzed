# json-document-entity-recogonized-sentiment-analyzed

You are given a JSON file (tweets.json) that contains tweets (sentences) along with the name of
the author.
Objective 1: Get the most frequent entities from the tweets.
Objective 2: Find out the sentiment/polarity of each author towards each of the entities.
Sample Input:
Assume we have only 4 tweets:
Tweet1 by Author1: Pink Pearl Apples are tasty but Empire Apples are not.
Tweet2 by Author2: Empire Apples are very tasty.
Tweet3 by Author3: Pink Pearl Apples are not tasty.
Tweet4 by Author1: Pink Pearl Apples smells really good.
Sample output:
Entities in the topics extracted: Share a CSV with extracted entities and the frequency of the  extracted entity from all the tweets in the following format
objective1.csv
entity frequency
Pink Pearl Apples 2
Empire Apples 2
Sentiment/polarity of Authors: Share a CSV file with predicted sentiment values with extracted
entities as columns and unique authors as rows. See the example CSV below.

objective2.csv
entity author_name overall_polarity
Pink Pearl Apples Author1 Positive
Empire Apples Author1 Negative
Empire Apples Author2 Positive
Pink Pearl Apples Author3 Negative
