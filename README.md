# ML

1.
Part A
P(Y∣TC) = .5/.7 = .714

Part B
0.1988

3.
I conclude that yes the green buildings charge more for rent and have a higher leasing rate, however costs for these green rated buildings are also higher. The data could also be a bit skewed as on average the green buildings are larger and newer, have more recent rennovations, and have a greater proprtion of buildings classified as class_a. So yes when looking at possible revenue they are not wrong in that you can earn more. Must also see that 
the type of green_rating also matters in terms of costs, rent, and leasing rate. concluding that its more than just 
building green but also choosing over LEED or Energystar.

4.
  we see that many it is the busiest during the time periods between 3pm-5pm with the peak being at 4pm.
this can be seen as it is the time where students are largely going to class and taking the bus 
and when classes finish and they take the bus home
  we see many people getting off the bus in the early morning 7-10am this can be part of studnets having to class
and commuting from off-campus locations but could also be attributed to workers going to work
  we see that the bus is largely used during the weekdays, or school days by drastic amounts in comparison to the 
weekends
  we see that the buses are the lease active in November which makes sense since students
are gone during the november for 1 week
  we also see that many more people opt to use public transport when its not too cold or not too hot
a reason as to why the buses were also not being used in both drastic temperatures was also because students 
were gone in November

5.   
tSNE plot seems to be doing the best in splotting the red and white wines in comparison to PCA and K-means.
many points are overlapping in the K-menas and for the PCA plot there are distinct clusters but in comparison the 
tSNE has a more distinct line between them and both have some overlap of points

6. 
after doing clustering and seperating it into 3 clusters. we are able to see that in cluster 0 that the sports,religion, parenting, and food characteristics are higher. in cluster 1 chatter, photo_sharing, health, and cooking are higher in charactersistics. lastly in cluster 2 we see that chatter is the only one that is higher than normal, it can be seen as the cluster that is grabbing the rest of the data. when increasing the cluster size this continued to occur therefore I kept it at size 3 

7. 
    Q: What similarities are there between the texts?, what are common words used?

    A: Decided to do a PCA and clustering with the text data. trying to figure out any commonality within the data. helps mark what texts are similar through PC and also list out the words

    R: had 50 clusters due to the size of the data and created a plot of the PC1 v PC2. printed out the common words within each cluster and also the top words for each PC

    C: for PC1 we a lot of words pertaining to a certain topic with words such as "beijing, china, leader, chinese, political" focusing on something about china and politics. PC2 however is picks up more on trade or money with words pertaining to "index, points, composite, stocks, percent, gold". We can conclude that there are many text pertaining to some social and global aspects of trade and politics

8. 
will read in the dataset and split absed on ',' and check for all the unique items in that are mentioned. then will onehot encode to binary signaling if that item was present in a certain row.

chose to set min_support to .001 since I chose to look at only 1 item in a set. So the more datapoints the better
put confidence to be at .4 due to the fact at too large of a confidence it is unable to capture a lot of points
for lift I had it show the top 10 and we can evaluate that they are all well above 1, showing good association. the results seem to make sense and true









    
