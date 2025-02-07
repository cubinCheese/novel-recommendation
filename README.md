# novel-recommendation


# vscode > select anaconda "novel-recommendations" env
# "conda install scikit-learn" to install sklearn in anaconda.navigator environment




### From 02_data_visualization ###
### Data exploration ###

![alt text](image-assets/fig_02-01.png)

![alt text](image-assets/fig_02-02.png)

* Scatter plot of readers vs tags
* Rough idea - less tags correlates to less readers
![alt text](image-assets/fig_02-03.png)


* cosine similarity based on 'tags' and 'genres' column
* example. compared to "Reverend Insanity"
* similarity values seemed moderate, top 10 ranging from 0.49 to 0.57
* in fact, IRL, "Pursuit of The Truth" is recommended by other users as a similar novel
![alt text](image-assets/Fig_03-01.png)

* Another example
![alt text](image-assets/Fig_03-02.png)