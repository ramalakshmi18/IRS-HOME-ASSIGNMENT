# IRS-HOME-ASSIGNMENT
What is an Information Retrieval System?
Simply put, an IR system allows it users to efficiently search documents and retrieve meaningful information based on a search text/query.

![alt tag](https://raw.github.com/sudhanshumittal/Information-retrieval-system/master/images/img.gif)
A good IR system should -
a) be fast
b) be space efficient
c) be accurate
d) understand the users query in an 'intelligent' manner

What constitutes this project?

This project is a simple IR system with the following constituents -
1) an efficient document indexing data structure
2) a ranking algorithm to retrieve the most relevant documents to a query
3) a page ranking algorithm to order the retrieved documents based on their 'importance'
4) a summarization algorithm to display the summary of each document with its web link
How to use it?
goto src directory run python main.py [-c] ( -c for index rebuilding )
Note: This system can be integrated with a web based UI by calling the appropriate API from the package. However, The UI developed for the project has not been added to Github.

Details for nerds
stopwords - using the list of stop words provided for the corpus
stemming - using porter stemming implemented in python
indexing - trie using bio library in python
ranking - Tf-IDf, tf => augmented
precision - mean average precision ~ 1.4
page ranking -google page ranks calculated in matlab
summarization- supervised keyphrase extraction
