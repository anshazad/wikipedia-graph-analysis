# wikipedia-graph-analysis

Scraped Wikipedia data(Mathematics concepts) to create a Wikipedia graph and train a neural network to predict the difficulty of the page's content.
Recommending topics to study before learning a topic based on the level of difficulty of the page

In this project, I learned how to analyze Wikipedia Graph. I focused on the articles in the mathematics category. Assume that there are students who are preparing for the JEE-Advanced exam.

We need to generate a sub-graph(s) of Wikipedia articles that are relevant to their study.  

Furthermore, we will also try to give them an order in which these should be read (traversal algorithm). These traversals can be organized by subjects etc. 

This is a complex task, I am breaking it down into suggested parts.

a. Scrape and Label articles according to complexity for someone who has just passed 10th class. We would like to have labels: {Beginner, Intermediate, Advanced, Irrelevant}
https://docs.google.com/spreadsheets/d/1A8G-00Y8yIR6XCm3xf-tAWF2Z_WwU13R6gS8SzEqzGU/edit#gid=0

b. Build the Wikipedia Graph along with attributes (including keywords, tags, NLP features etc.)

c. Create additional features based on Graph using concepts like centrality metrics, clustering coefficient. 

d. Development of Node classification Models

e. Graph Traversal and Article Ordering Algorithm
