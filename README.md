# Flatiron School Module 1 Project: IMDb Web Scraping 

## Data Scraping the TOP 250 movies of all-time in IMDb. Initially sorted by number of votes in descending order. 

This project incorporates some data scraping, data wrangling, data cleaning, and visualizations. 

<img width="1440" alt="imdb" src="https://user-images.githubusercontent.com/53641091/74690899-7f8ac800-5195-11ea-8e7a-37a29a9c56ba.png">

## Example of dataframe:

This project makes use of various modules including beautifulsoup, pandas, matplotlib, seaborn, and numpy. 
Below is the dataframe that is created displaying the relevant information we need to create the visualizations and explorations. 

<img width="1029" alt="Screen Shot 2020-02-17 at 3 13 23 PM" src="https://user-images.githubusercontent.com/53641091/74691828-3d638580-5199-11ea-83ee-3871c386c4d1.png">

## Purpose of project: 

The purpose was to explore the data within IMDB's TOP 250 movies of all-time and determine if there were any meaninful conclusions I could derive from such. I was looking for any correlations between the features I scraped that would eventually be used to drive my visualizations. 

## Questions: 

- What genre appears to be most promising for a company that wants to break into the film-making industry?
- What directors and actors fare best in said genre? And how do they compare amongst each other? 
- Are there any meaninful correlations or relationships to look at that might give us a little more insight into the film-making industry?

## Findings:

<img width="872" alt="Screen Shot 2020-02-17 at 4 31 54 PM" src="https://user-images.githubusercontent.com/53641091/74693996-16aa4c80-51a3-11ea-847e-129dcfbb2587.png">

The action genre seems to be most promising in terms of breaking into the industry. The spread represents many more data points then do the other genres. Although action doesn't have the films with the highest metascores, they are represented much more amongst the films in the TOP 250 IMDb movies of all-time. If a company decided to go ahead and produce an action-packed film their chances of making it into the TOP 250 would be much greater than if they were to go with any other genre. 

* *Sidenote: If a company decided to go ahead and make a horror film or western film, they would have to execute and exceptional film with an extremely high metascore in order to have any remote chance of making it into the TOP 250*

<img width="952" alt="Screen Shot 2020-02-17 at 5 06 09 PM" src="https://user-images.githubusercontent.com/53641091/74695166-d4cfd500-51a7-11ea-9e46-ab6a13743998.png">

The director that seems to garner the most votes in the action genre appears to be Christopher Nolan when looking at the TOP 20 action films. The Dark Knight is his most successful film with almost double the votes compared to his other films. James Cameron comes in second with Avatar amassing around 1.08 million votes. It'd be smart for the company to hedge its bets and hire Christopher Nolan as their producer if they aspire to break in. 

<p align="center">
<img width="418" alt="Screen Shot 2020-02-17 at 4 59 35 PM" src="https://user-images.githubusercontent.com/53641091/74694924-ecf32480-51a6-11ea-8539-588c8d38150f.png">
</p>

When looking at the top actors for the TOP 20 action films we see 3 names stick out above the rest. They are: Christian Bale, Mark Hamill, and Robert Downey Jr. With a 3,3, and 2 count, respectively amongst the TOP 20. If the company had to go with one of these stars, I would definitely recommend they go with Christian Bale. And you may be asking why not Mark Hamill since he is also in 3 of the TOP 20 action films? ... Hopefully the scatterplot below illustrates this a little better.  

<img width="973" alt="Screen Shot 2020-02-17 at 5 15 11 PM" src="https://user-images.githubusercontent.com/53641091/74695512-18770e80-51a9-11ea-9dd1-842c44851231.png">

As you may have become aware by looking at the scatterplot above, Christian Bale's appearances in the Batman Begins, The Dark Knight Rises, and The Dark Knight all have more votes than do the films where Mark Hamill is in. Those being Stars Wars: Episode IV- A New Hope, Star Wars: Episode V- The Empire Strikes Back, and Star Wars: Episode VI- Return of the Jedi. The film with the least votes for Christian Bale has more votes than the movie starring Mark Hamill with the most votes. Also, Christian Bale's films are all directed by Christopher Nolan, whereas Mark Hamill's films are all directed by three different directors. Without a doubt, the Christopher Nolan-Christian Bale duo would be a banger in the industry and would definitely disrupt the space in a positive way. The company's venture would certaintly reap the rewards. 

<p align="center">
<img width="454" alt="Screen Shot 2020-02-17 at 5 34 57 PM" src="https://user-images.githubusercontent.com/53641091/74696277-d7342e00-51ab-11ea-8527-69da4ee4da97.png">
</p>

This is an interesting correlational heatmap that may prove to be very valuable for future work. 

<p align="center">
<img width="431" alt="Screen Shot 2020-02-17 at 5 41 18 PM" src="https://user-images.githubusercontent.com/53641091/74696547-b9b39400-51ac-11ea-8568-2a6e2bd74777.png">
</p>

* *An interesting exploration and subsequent insight that was inspired by the correlational heatmap above was the notion to look at the correlation between time and gross in terms of genre. What can be derived from this is that the films in the action genre tend to have a higher gross as the timespan of the film increases. What this tells the company is that when making their action film, they should try to make it on the longer side.*

## Key takeaways:

1. Stick with the action genre. The proof is in the pudding. 
2. Try your best to hire Christopher Nolan as the director for your film. 
3. Christian Bale is by far your safest bet at a quality action-packed film. 
4. Make the action film longer. The longer the timespan the better it does in the box-office in terms of gross. 
