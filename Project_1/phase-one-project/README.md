<hr style="border:1.5px solid gray"> </hr>


<font size=4>__Author__: Matthew Noonan</font>


<font size=5>__Overview__</font>
<hr style="border:1.5px solid gray"> </hr>

<font size=4>Microsoft Studios, a newly formed division of Microsoft, is looking to make its 
    movie production debut. To that end, it wants to know what movies typically perform well.
    We arrive at three recommendations for its movie-making debut by analyzing various 
    movie information databases using pandas and visualizations. Our recommendations were 
    drawn from the results of budget and genre data.
    

<font size=5>__Business Problem__</font>
<hr style="border:1.5px solid gray"> </hr>We asked:<br>

     - How are film budget and worldwide gross related?
     
     - Do different genres have different profitability ratios?
     
     - Which genres have the highest average grosses?

<font size=5>__Data__</font>
<hr style="border:1.5px solid gray"> </hr>The data comes from several
online information databases (IMDB, TheNumbers, and BoxOfficeMojo).
Each row contains information about individual films, each source with
different features. We chose these data sources for ease of use, variety
of data, and size.

<font size=5>__Methods__</font>
<hr style="border:1.5px solid gray"> </hr>The data was prepared and cleaned
of NaN's and non-sensical entries; some features were dropped entirely, and 
other features created. 


<font size=5>__Results__</font>
<hr style="border:1.5px solid gray"> </hr>We found that budget and worldwide
gross were tightly correlated.<img src="https://github.com/mcn9284/Phase-1-Project-b/blob/main/Project_1/phase-one-project/Images/budgetvsgross.png?raw=true">


That profitability was higher with some genres 
<img src="https://github.com/mcn9284/Phase-1-Project-b/blob/main/Project_1/phase-one-project/Images/profitabilityvsgenre.png?raw=true">

That ratings and gross were not tightly coupled.
<img src="https://github.com/mcn9284/Phase-1-Project-b/blob/main/Project_1/phase-one-project/Images/ratingsvsgross.png?raw=true">

Recommendations:

     - with respect to budget, choosing moderate budget yields higher returns
     - Action, adventure, animation, and scifi were most profitable
     - Fittingly, these same genres had higher grosses than other genres

<font size=5>__For More Information__</font>
<hr style="border:1.5px solid gray"> </hr>For further analysis, please see our
full [jupyter notebook](./Untitled1.ipynb)


