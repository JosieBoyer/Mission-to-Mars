# Mission-to-Mars

## Deliverable 1 :

We created a file with Jupyter Notebook, ["Mission_to_Mars_Challenge.ipynb"](https://github.com/JosieBoyer/Mission-to-Mars/blob/main/Mission-to-Mars-main/Mission_to_Mars_Challenge.ipynb), to scrape the various sites and verify our data, to help build our Flask app.  Having already built code to scrape the earlier elements, this deliverable asked us to refactor that code to scrape the full-res image URLs and image titles from [marshemispheres.com](http://marshemispheres.com).

![deliverable_1.png](https://github.com/JosieBoyer/Mission-to-Mars/blob/main/Mission-to-Mars-main/resources/deliverable_1.png)

## Deliverable 2:

We created [scraping.py](https://github.com/JosieBoyer/Mission-to-Mars/blob/main/Mission-to-Mars-main/scraping.py) to be the workhorse of our scraping site.  Within the file, we created the function "scrape_all()" to return the data we want, but referencing several other functions (mars_news, featured_image, mars_facts) within it.  

![deliverable_2b.png](https://github.com/JosieBoyer/Mission-to-Mars/blob/main/Mission-to-Mars-main/resources/deliverable_2b.png)

Once built, this deliverable asked that we introduce a new function (which I named mars_hemispheres) to scrape and return the titles full-resolution image URLs of Mars' hemispheres, so that they can be added to our MongoDB and finally referenced in our web template.

![deliverable_2a.png](https://github.com/JosieBoyer/Mission-to-Mars/blob/main/Mission-to-Mars-main/resources/deliverable_2a.png)

## Deliverable 3 (Add Bootstrap 3 Components)

Our final task was to take the constructed local web page and add styling elements from Bootstrap 3, not only to make the page stand out but also for compatability purposes when viewed on different sized screens. 
- I changed several font and element colors, including the "Scrape New Data" button that appears at the top of the screen.
- Images were added as backgrounds for both the jumbotron element and the screen as a whole.
- Added transparent backgrounds to the hemisphere thumbnail section, so the background image isn't completely covered.
- A "Last Updated" readout display was added just below the jumbotron, to inform the user how recent the saved data is.
- Added the code ```<div class="col-xs-12 col-md-6 col-sm-4 col-lg-6">``` to the hemisphere thumbnail section, in order to resize the thumbnail grid for phones, tablets, medium and large desktops.  In the screenshot below, you'll see the page is mobile responsive, and resizes the  various elements so they can be stacked above each other.

![deliverable_3a.png](https://github.com/JosieBoyer/Mission-to-Mars/blob/main/Mission-to-Mars-main/resources/deliverable_3a.png)

## Summary

![webpage_snapshot.png](https://github.com/JosieBoyer/Mission-to-Mars/blob/main/Mission-to-Mars-main/resources/webpage_snapshot.png)
