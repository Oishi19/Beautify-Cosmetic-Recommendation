# Beautify - a Cosmetic Recommendation System
 *Mapping cosmetic items based on their ingredients similarities and giving content-based filtering recommendation*

<br>

## ***1. What Can We Do for a Healthy Skin?***
It's always so challenging for me to decide which new cosmetic product will work best for me.   It can be really  unsettling because I frequently experience skin problems after trying something new. You might be able to empathize with this situation if you share my experience. We are aware that the back of the cosmetic bottles will provide the details we require here. But if you aren't a chemist, it's incredibly difficult to deduce anything from these product names.
So instead of just being worried about new choices, I decided to build a simple cosmetic recommendation on my own.
<br>

* **Applied skills:** Web scraping with Selenium. Text mining and word embedding. Natural Language Processing. Dimension reduction with t-SNE. Content-based Recommendation Filtering using Cosine similarities of chemical compositions. Interactive Visualization with Bokeh.

<br>

## ***2. File Details***
- **[01.scraping.py](https://github.com/jjone36/Cosmetic/blob/master/01.scraping.py)** : Web scraping data on Nykaa with Selenium.

- **[02.preprocessing.py](https://github.com/jjone36/Cosmetic/blob/master/02.preprocessing.py)** : Data cleaning & preprocessing.

- **[03.modeling.py](https://github.com/jjone36/Cosmetic/blob/master/03.modeling.py)** : Creating a database for the whole items and modeling with word embedding and dimension reduction technique.

- **[04.Visualization.ipynb](https://github.com/jjone36/Cosmetic/blob/master/04.Visualization.ipynb)** : Visualizing the items as an interactive bokeh app with Bokeh

![map](https://github.com/jjone36/Cosmetic/blob/master/image/map.gif)

<br>

## ***3. What's Next?***
- Gather more data and make my own database with MySQL.
- Create a practical Web Page/App using Flask  
- Create a better comparing model through Neural Network
