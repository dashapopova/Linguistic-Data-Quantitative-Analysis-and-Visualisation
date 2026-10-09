## Practice 10/10/2026

## Step 1

From the WordNet database take the synset 'search.v.01'. Extract lemmas that belong to the synset for all the languages of the database.

## Step 2

For each lemma of each language create a list of synsets that that lemma belongs to. Leave only synsets that have more than 3 lemmas from our original list. Those synsets will become the nodes of our graph. 

## Step 3

Now let's define the edges. Put an edge between two synsets if there is at least one language where a lemma belongs to both synsets. We'll draw a weighted graph: the weight of an edge will represent the number of lemmas that belong to both nodes.

## Step 4

Let's analyze the graph. How many connected components do we have? What is the density? What synsets have the highest weighted degree? What nodes are central (use different methods: degree centrality, eigencentrality)? Split the graph into communities, comment upon the results. 

## Step 5

Draw a graph similar to the one in Step 3, but put an edge only in cases where there are at least 5 lemmas that belong to two synsets. We are now looking for more stable colexifications. Analyze the new graph (as outlined in Step 4). Compare the graph from Steps 3 and 4 with the new graph. What has changed? Which of the two graphs seems more interesting to you and why?

## Step 6

What can you say about the colexification patterns in the SEARCH domain based on your graphs? 

## Step 7

Compare your results to the subgraph LOOK FOR from CLICS

https://clics.clld.org/parameters/1468#1/21/153

https://clics.clld.org/graphs/SHAVE
