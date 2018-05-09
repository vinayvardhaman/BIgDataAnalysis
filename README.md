# BIgDataAnalysis

This project involves (i) Data aggregation from more than one source using the APIs (Application programming interface) exposed by data sources (ii) Applying classical big data analytic method of MapReduce to the unstructured data collected (iii) Building a visualization data product.

We chose the topic of blockchain and cryptocurrency for data collection.

Data is aggregated from multiple sources like Twitter and NY Times Articles.

Code and executed MapReduce word count on each of the data sets. Map will clean and parse the data sets into words, remove stop words, and reduce will count the useful words. Used keywords like bitcoin to obtain comparable results in the output.

Visualized each of the outputs using d3,js on a simple web page.

Repeated the steps above for larger data set collected over week. More convergence in the output was observed.

Designed a web page and fed the results by embedding d3.js code (with replaceable worldclouds) in it, finalizing the display of results. Selecting a predefined topic in the drop down will return the word cloud associated with that topic!

Extended the analysis to find the word co-occurrence in the data. Wrote another MapReduce job to emit pairs of co-occurring words on a smaller dataset(top 10 frequent words).
