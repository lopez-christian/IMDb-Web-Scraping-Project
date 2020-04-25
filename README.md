## IMDb Web Scraping

# Data Scraping the TOP 250 films of all-time in IMDb 
# Sorted by number of votes in descending order

This project incorporates some data scraping, data wrangling, data cleaning, and visualizations. 

<p align="center">
<img width="1440" alt="imdb" src="https://user-images.githubusercontent.com/53641091/74700166-9e01bb00-51b7-11ea-8a10-0de37c110df1.png">
</p>

# Example of dataframe:

<p align="center">
<img width="1029" alt="Screen Shot 2020-02-17 at 3 13 23 PM" src="https://user-images.githubusercontent.com/53641091/74700223-beca1080-51b7-11ea-88b2-4166b6e38825.png">
</p>

# Purpose of project:

The purpose of the project was to explore the data within IMDb's TOP 250 films of all-time and determine if there were any meaninful conlcusions I could derive from such. I was looking for any correlaitons between the features I scraped that would eventually be used to drive my visualizations. 

# Questions/Answers:

**What genre appears to be the most promising for the company that wants to break-into the film-making industry?**

<p align="center">
<img width="872" alt="Screen Shot 2020-02-17 at 4 31 54 PM" src="https://user-images.githubusercontent.com/53641091/74700327-018be880-51b8-11ea-9559-372331783dcf.png">
</p>

The action genre seems to be the most promising in terms of breaking into film industry. The spread represents many more data points then do the other genres. Although action doesn't have the films with the highest metascores, they are represented much more amongst the films in the TOP 250 IMDb movies of all-time. If a company decided to go ahead and produce an action-packed film, their chances of making it into the TOP 250 would be much greater than if they were to go with any other genre. 

*Sidenote: If a company decided to go ahead and make a horror film or western film, they would have to execute an exceptional film with an extremely high metascore in order to have any remote chance of making it into the TOP 250.* 

**What directors and actors fare best in said genre? And how do they compare amongst each other?**

<p align="center">
<img width="952" alt="Screen Shot 2020-02-17 at 5 06 09 PM" src="https://user-images.githubusercontent.com/53641091/74700960-0fdb0400-51ba-11ea-807e-8e35259f8f5a.png">
</p>

The director that seems to garner the most votes in the action genre appears to be Christopher Nolan when looking at the TOP 20 action films. The Dark Knight is his most successful film with almost double the votes compared to his other films. James Cameron comes in second with Avatar amassing around 1.08 million votes. It'd be smart for the company to hedge their bets and hire Christopher Nolan as their director if they aspire to break in. 

<p align="center">
<img width="418" alt="Screen Shot 2020-02-17 at 4 59 35 PM" src="https://user-images.githubusercontent.com/53641091/74700908-e91ccd80-51b9-11ea-9679-cad744bfc183.png">
</p>

When looking at the top actors for the TOP 20 action films, we see three names stick out above the rest. They are: Christian Bale, Mark Hamill, and Robert Downey Jr. With counts of 3, 3, and 2, respectively. If the company had to go with one of these stars, I would definitely recommend they go with Christian Bale. And you may be asking yourself, why not Mark Hamill, since he is also in the TOP 20 action films? ... Hopefully, the scatterplot below illustrates my point a little better. 

<p align="center">
<img width="973" alt="Screen Shot 2020-02-17 at 5 15 11 PM" src="https://user-images.githubusercontent.com/53641091/74701159-b58e7300-51ba-11ea-9d1e-611d3f704cb1.png">
</p>

As you may have become aware by looking at the scatterplot above, Christian Bale's appearances in the Batman Begins, The Dark Knight Rises, and the Dark Knight all have more votes than do the films where Mark Hamill is in. Those being Star Wars: Episode IV- A New Hope, Star Wars: Episode V- The Empire Strikes Back, and Star Wars: Episode VI- Return of the Jedi. The film with the least votes for Christian Bale has more votes than the movie starring Mark Hamill with the most votes. Also, Christian Bale's films are all directed by Christopher Nolan, whereas Mark Hamill's films are directed by three different directors. Without a doubt, the Christopher Nolan-Christian Bale duo would be a banger in the industry and would definitely disrupt the space in a positive way. The company's venture would certainly reap the rewards. 

**Are there any meaningful correlations/relationships to look at that might provide more insight into the film-making industry?**

<p align="center">
 <img width="454" alt="Screen Shot 2020-02-17 at 5 34 57 PM" src="https://user-images.githubusercontent.com/53641091/74701975-64cc4980-51bd-11ea-991d-36cc3ec82c59.png">
</p> 

This is an interesting correlational heatmap that may prove valuable in future work. 

<p align="center">
<img width="431" alt="Screen Shot 2020-02-17 at 5 41 18 PM" src="https://user-images.githubusercontent.com/53641091/74702031-9218f780-51bd-11ea-8337-26be2955f803.png">
</p>

An interesting exploration and subsequent insight that was inspired by the correlational heatmap above was the notion to look at the correlation between times and gross in terms of genre. What can be derived from this is that the films in the action genre tend to have higher gross as the timespan of the film increases. What this tells the company is that when making their action film, they should focus on making it on the longer side. 

# Key takeways:

**1. Stick with the action genre.**

**2. Try your best to hire Christopher Nolan as the director for your film.**

**3. Christian Bale is by far your safest bet at a quality action-packed film.** 

**4. Make the action film longer. The longer the timespan the better it does in the box-office in terms of gross.**
