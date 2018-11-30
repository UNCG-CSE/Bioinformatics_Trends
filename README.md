Centered on bioinformatics Scopus research papers’ data, our goal was to predict the citation count of a paper. This project
involved four separate phases, each phase focused on Machine Learning and its improvement, due to how intimately Machine
Learning is tied to our prediction success.

The first phase of the project consisted of orienting ourselves with our data and what we want to do with it. Asking questions
such as: what is the nature/origin of our data, what is the size of our data, what is our goal.

The second phase involved converting, organizing, and cleaning our data. Our data was originally in json format, so we had to
convert from json to csv, handle null fields, handle lists. Ultimately, we prepared our data for the purposes of visualization
and machine learning.

The third phase consisted of the visualization and understanding of our data, essentially educating ourselves on our data to
make sound decisions for phase four (Machine Learning). We visualized and gained a big picture understanding of our target
column, 'Citations'. Then we went through each feature, one by one, trying to understand what relationship they may or may not 
have with 'Citations'.

The fourth phase involved NLP processing and Machine Learning. The NLP techniques helped us create new features for Machine 
Learning to increase our accuracy. The NLP techniques included: removing special characters and stopwords, stemming, LDA 
(TFIDF), and encoding. For Machine Learning, we applied Random Forest and XGB. The best accuracy achieved was 74% using XGB with 
Log Transformation.

Tasks were divided/completed in two ways, depending on the context:

a) Group collaboration: we would reserve a room in the library and work on the project in unison.

b) Phase-by-phase division: we would divide up specific tasks for that particular phase, and then combine our efforts the next 
time we met. This division style only happened on occasion.

Members and Related Tasks: 
- Mouna https://github.com/mounakalidindi

- Logan https://github.com/LoganHornbuckle

- Darpan https://github.com/djhawar

- Steve https://github.com/stevieclean

- Luke https://github.com/lukeusername
