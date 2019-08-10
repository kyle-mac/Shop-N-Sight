## MIDS Capstone 2019 - Shop-'N-Sight

Team Members: Walt Burge, Arunima Kayath, Kyle MacIlvain, Lalit Verma

### Overview

Shop-'N-Sight is a recommendation system with an interactive web interface to help users find the specific products they are looking for. It enpowers the user to provide their specific product requirements with detailed features and then finds products with those features for them.

An eCommerce outfit offering great product assortment needs to think about how to solve the paradox of choice for consumers, enabling them to find what they are looking for quickly. They can also help them discover niche and long tail products. Recommendation algorithms help solve these problems, and are a key component in successful online strategy. They are now present throughout the online customer journey, showing products similar to what they are looking at. 

### Techniques

We implemented two recommendation algorithms to find and recommend similar products, and an interactive web interface that takes input from the users to help them find the exact product they are seeking. The first algorithm is matrix factorization of customer item ratings to find item latent features and similar items based on these features. The second algorithm uses a series of natural language processing techniques and clustering with HDBScan to extract product features from customer reviews and product descriptions. These are then used to  find similar items to the ones the user is looking for.

The interactive web interface displays the extracted text features. The user can interact with the site to select specific products and specific features they want to guide their recommendation to find a product that meets their specific needs.

### Data

This project is based off of the Amazon Product Dataset hosted by Julian McAuley, UCSD http://jmcauley.ucsd.edu/data/amazon/
which contains product reviews and metadata from Amazon, including 142.8 million reviews spanning May 1996 - July 2014.

For this project we limited ourselves to the Toys and Games categories with reviews (2,252,771 reviews)	metadata (336,072 products) and filtered down towards products with multiple reviews.

The end idea is that this application could be expanded towards all categories in the future.

### Application

[Click Here to Try the App!](http://ec2-54-173-219-194.compute-1.amazonaws.com:4200/home)
![Image](https://raw.githubusercontent.com/kyle-mac/capstone_web_deliverable/master/webpage.png)
