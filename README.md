# novel-recommendation

This project utilizes the [novelupdates](https://www.novelupdates.com/) database to explore and build recommendation models.

The dataset used is a 20,000+ novel dataset scraped from [novelupdates](https://www.novelupdates.com/), courtesy of [shaido987](https://github.com/shaido987/novel-dataset). 

For those unaware: Novelupdates is an online platform and community database that tracks and organizes translated light novels, web novels, and other types of translated literature, primarily from Japanese, Chinese, and Korean. Offering a place for reader reviews, ratings, rankings, and discussion forums.


## Data exploration 

Description: Figure exploring tags used in different fictional works within novel database.

![alt text](image-assets/fig_02-01.png)


Description: Figure looking at the least used tags

![alt text](image-assets/fig_02-02.png)


Description: 
- Scatter plot of readers vs tags
- Novels with fewer tags correlate with fewer readers

![alt text](image-assets/fig_02-03.png)



## Similarity Model 

Description:
* We finished reading our novel and we want to determine which novel we should read next, so if we asked for novels according to how similar they are by 'tags' and 'genres'. What would we get?

- Here, novel "Reverend Insanity" is compared to our dataset of novels, by 'tags' and 'genres'. 
- Resulting in the following similarity scores in the figure below.
- Similarity values seemed moderate, top 10 ranging from 0.49 to 0.57
- So these were the top 10 novels with the most likeness to "Reverend Insanity".

![alt text](image-assets/Fig_03-01.png)

* Note. In reality, many users have recommended the novel "Pursuit of The Truth" as a novel similar to "Reverend Insanity". And so, we can see that there is merit to factoring in a similarity model based on 'tags' and 'genres'.


Description:
* Additional example, using "Warlock of the Magus World" as the point of comparison.

![alt text](image-assets/Fig_03-02.png)


* A next step in improvement, would be novel ratings, rankings, individual user-created reading lists, and potentially the fully detailed novel reviews left by users.
