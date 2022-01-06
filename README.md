# House listings, web scraping and Tableau


In this project I scraped the first five pages of listings concerning vacation rentals in the Lisbon district shown in Imovirtual. 
I found 69 unique listings (all the descriptions were different) and extracted variables such as price, area, number of bedrooms,... as well as features listed.
I also saved string variables such as title and description. I used Python, BeautifulSoup and Pandas.

I cleaned the data using Python, Pandas, and Tableau Prep.

I created a story using Tableau, of mostly exploratory analysis. The story contains sunburst, butterfly and circle grid charts created using Tableau.

The story can be found at https://public.tableau.com/app/profile/f.tima.rosa/viz/ListingsofvacationrentalsintheLisbondistrict/Story1?publish=yes 

The repository contains:

- imovirtual.ipynb : Jupyter notebook consisting of the scrapping and cleaning of the data
- imovirtual.csv : Resulting dataset from imovirtual.ipynb 
- after_tableau_prep.csv : Dataset after following Tableau Prep recommendations
- tableau_analysis.twb : Tableau workbook showing the data analysis and story
- Story.pdf : Pdf of the story created.
