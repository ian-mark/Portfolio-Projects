Mid-term Project Description
================
![image](https://content.fortune.com/wp-content/uploads/2016/10/1000638_books_landing-page_hero_desktop.jpeg)

Big, online data have several distinctive attributes. The presence of a
'timestamp' is certainly one of these attributes. An example of
timestamped data would be the 'listening,' two-mode network behind
Spotify (i.e., who listens to what, when). 

Timestamped data open up the possibility to analyze **how** business,
economic, or social variables evolve in 'real-time.' This has radically
impacted the analysis of a broad range of phenomena (e.g., consumer
behavior, design and monitoring of product launch campaigns).

However, data granularity creates distinctive data visualization
challenges. When it comes to creating a new chart, the designer has to
consider a broad range of information needs that could be satisfied with
the timestamped data at hand. For example the audience may want to get
insights about:

1. the general tendency of the focal variable over time (e.g., the
   trajectory of popularity of the average 'pop' album);
2. the distribution of the focal variable at multiple points in time;
3. the evolution of the focal variable for specific cases (e.g.,
   specific products);
4. the differences/similarities in 1, 2, and 3 across categories of
   entities (e.g., types of products).

'Space' constraints represent an additional layer of complexity.
Sometimes designers have only one chart to serve these multiple
information needs.

For their mid-term project, groups are supposed to use the Amazon
dataset [Jeff McCauley](wwww.mccauley.com) has put together, in order to
create a Matplotlib figure with the following characteristics:

+ the figure has to fit the A4 layout, landscape orientation;
+ four (4) plots populate the figure;
+ in terms of information needs, users would like to see the following
    elements:
  - the trajectory in the count of ratings received by product across time 
      (since the very first score up to six months later; exclude products whose 
      first score has been posted by less than six months);
  - the association between the trajectory in the count of ratings and 
      product attributes (e.g., product-market category, price);
  - the association between the trajectory in the count of ratings and 
      the timing/pace with which ratings are posted.

The **audience** for this chart is a team of experienced marketing
analysts who want to understand how/why attention (measured in terms of count of
ratings) develops around new products.  The chart is meant to serve both
exploration and presentations goals – analysts will use it (i) to
speculate about the factors that account for the trajectory in the
count of ratings; (ii) to update their client with a PowerPoint alike
slide-show.

Data 
====

The data for this project is publicly available at this
[link](http://jmcauley.ucsd.edu/data/amazon/). 


Deliverables
-------------------------

+ Copy of the Jupyter notebook
+ Copy of the final chart (.pdf format)
+ Final report with the following:
   - A justification of the critical design decisions against the visualization wheel proposed by Alberto Cairo
   - An effective, concise description of the key insights emerging from the visualisation

