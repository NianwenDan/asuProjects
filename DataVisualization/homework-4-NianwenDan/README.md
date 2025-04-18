# Homework #4: Custom Visualization Design

In this homework, you will create a custom visualization that goes beyond the "common chart types" that you already exist. **This assignment is worth 10 points.**

The audience for this visualization is visitors to a musuem. The goal is to create a visually interesting and informative visualization graphic/infographic exhibit that communicates (some or all of) the dataset effectively and in a creative manner (as opposed to supporting in-depth analysis such as might be done by domain experts).

There are five datasets available for this homework (choose one).

* Washington DC Historical Weather 2015/8~2024/07 ([source](https://www.kaggle.com/datasets/taweilo/washington-dc-historical-weather-20158202407)): a dataset showing daily weather in Washington DC.
* Superhero Power Analytics ([source](https://www.kaggle.com/datasets/shreyasur965/super-heroes-dataset)): detailed information about 675 superheroes and villians.
* SpongeBob SquarePants Character Dataset ([source](https://www.kaggle.com/datasets/myticalcat/spongebob-squarepants-character-dataset)): detailed information about characters from the SpongeBob SquarePants universe.
* Top Influencers Crushing On Instagram ([source](https://www.kaggle.com/datasets/whenamancodes/top-200-influencers-crushing-on-instagram)): information about the most popular Insta influencers
* UFO Sightings ([source](https://www.kaggle.com/datasets/camnugent/ufo-sightings-around-the-world)): over 80k records about sightings of unidentified flying objects


## Requirements

* Create a page `index.html` in this repostory for storing your visualization. You'll also want to include your chosen dataset in your submitted repository.
    * You are allowed to modify/transform the base dataset as well. If you do this, you only need to submit the dataset files used in your submission (you don't have to submit the raw/original data files).
* Create a unique, D3-based visualization graphic (or infographic) that is not simply an existing technique or D3 block. 
    * Your visualization should be a "Custom" viusalization, as defined by the [Defining Custom Data Visualization](https://medium.com/@Elijah_Meeks/defining-custom-data-visualization-c20a64746d08) article and our corresponding lecture. In other words, it should be either a "modded," "combinatorial," or "novel" graphic.
    * You may import existing code, but you must document exactly what modifications you make in your writeup, and you should _substantially_ change any imported code that you build upon. If you're unsure what constitutes substantial, talk to the TA.
* You must visualize at least three different attributes in your museum exhibit. 
    * If you choose to represent the data spatially (e.g., using the lat/long coordinates in the data files, or if you create lat/long coordinates as a derived attribute), this counts as one attribute, so you need at least two more attributes in your exhibit.
* You are not required to visualize _all_ of the given data. You may focus on a specific topic or question that you want to address, and therefore you might only need to look at a subset of the data (attributes or items) to answer it. If you only want to visualize a subset of the dataset, you must include at least 30 data points (and these must be chosen in a way that helps to support your museum exhibit's story).
* You can reference the "Custom Visualization" lecture for some inspiration ideas. Another approach for creating a unique visualization is to create custom glyphs. Here are some examples that can provide inspiration.
    * [lalettura](http://giorgialupi.com/lalettura)
    * [film flowers](http://sxywu.com/filmflowers/)
    * [Visualizing Painter's Lives](http://giorgialupi.com/visualizing-painters-lives)
    * [How's life?](http://www.oecdbetterlifeindex.org/#/31111111111)
    * [Where the Wild Bees Are](https://www.scientificamerican.com/article/where-the-wild-bees-are/)
    * [Giorgia Lupi and Stefanie Posavec’s Life Data Visualizations](https://www.moma.org/magazine/articles/309)
    * [The Metropolitan Museum Partnership 2019](https://parsons.nyc/met-museum-2019/)
* You may choose to create either a static or interactive exhibit.
* Above or below your chart, have a title and include a short description that explains your design (marks, channels, interactions). Below that description, state which category of "Custom Visualization" your submission falls into (either modded, combinatorial, or novel), and explain why it does.
* If you created your visualization by modified an existing D3 block or example, also provide a link to the original source code and describe (in detail) how you modified it to create your chart.
* When you finish your 'exhibit', take a screenshot of your page and name it `asurite.png` after your ASURITE. (For example, mine would be `cbryan16.png`.) Include this png file in the base folder of your submission.

You are free (and encouraged!) to be creative on this assignment, including the use of abstract, artistic, thematic, esoteric, evocative, atmospheric, and illustrative designs. Don't submit just a basic D3 block (bar chart, scatterplot, pie/donut chart, line chart, node-link diagram, tree, etc.), or you'll receive a 0 on this assignment. Especially creative or interesting submissions are eligible for up to 2 points extra credit.
