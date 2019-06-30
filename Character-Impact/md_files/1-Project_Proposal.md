
# Measuring Characters' Screen Time from <i>The Office</i> and Their Impact on TV Show Ratings
## Project Proposal
### Alden Chico

----

## Problem

The value of the entertainment industry in 2014 was estimated at $537.5 billion dollars with the projected growth of the industry reaching $720.8 billion dollars by 2020 (1). In order to maximize the value of televised intellectual property, television networks need to create compelling storylines in their shows to vie for continued season renewal. 

Measuring character screen time would be a useful numeric metric to gauge how much emphasis the show is putting on each character. Furthermore, the Internet Movie Database (IMDb) stores user ratings online for each episode of a television series. So relating these two metrics on each episode of a season would be a useful tool for television show producers to make more informed decisions about character focus for successive seasons of the show.


![alt text](https://raw.githubusercontent.com/aldenmchico/Alden-Chicos-Portfolio/master/Character-Impact/ipynb_Files/reference/1-Project_Proposal/Statista-Entertainment-Chart.png "Logo Title Text 1")

<div align="center">Figure 1 - Value of the Entertainment and Media Market From 2011-2020 (in Billion USD) (1)</div>

For my project I'm going to develop software that can identify when characters are on the screen during episodes of <i>The Office</i>. I'll then relate character screen time during each episode to the episode’s user ratings and gather insights on how each character affects audience reception towards the show.




----

## Data

The data for this project comes in two sections. The first set of data I'll need to collect for this project comes from IMDb’s website. The IMDb updates their data files daily and makes them available for commercial and public use. So in order to complete this project, I'll perform filtering operations on these data sets to create a table that shows each episode of Season One of <i>The Office</i> alongside their corresponding user ratings.

For testing purposes, I'm using episodes of Season One of <i>The Office (USA)</i> because:

1. There's a small number of main and supporting cast members shown on screen throughout the entire season. 

2. The first season only contains six episodes which is a reasonably sized test case for this project. 

3. <i> The Office </i> is a popular TV show that millions of people know and love.


![alt text](https://raw.githubusercontent.com/aldenmchico/Alden-Chicos-Portfolio/master/Character-Impact/ipynb_Files/reference/1-Project_Proposal/Michael%20Scott%20Laughing.jpg "Everyone Loves The Office!")
<div align="center">Everyone Loves The Office!!! </div>

 

The second set of data I'll need to collect are pictures of each character in <i>The Office</i>. I'll use this data to train a facial algorithm that can identify characters when they're present on screen. After I train my algorithm, I'll first test it against other pictures of the actors/actresses and then test it against episodes of <i> The Office </i> to see if the facial recognition works properly.


----

## Method

1. Prepare television episode and user rating data from the first season of <i>The Office</i>.
2. Collect pictures of every character from <i>The Office</i> to train the facial recognition algorithm.
3. Test facial recognition on characters from <i>The Office</i> by labelling their faces on pictures.
4. Use the algorithm on video files from <i>The Office</i> and label the characters as they appear on screen.
5. Gather each character's screen time and relate that information with the episode data from IMDb's website.
6. Relay insights on Season One of <i>The Office</i> to make informed decisions on the direction to take the show for Season Two.

![alt text](https://raw.githubusercontent.com/aldenmchico/Alden-Chicos-Portfolio/master/Character-Impact/ipynb_Files/reference/1-Project_Proposal/Michael%20Excited.png "Facial Recognition Technology is EXCITING")
<div align="center">Facial Recognition Technology is EXCITING </div>


----

## Deliverable

I plan to update my progress through the project using blog posts using Github Gists powered by Jupyter Notebooks. The final blog post will bring together my insights on how characters in <i> The Office </i> affects the overall show’s ratings.


----

**Appendix**

(1) https://www.statista.com/statistics/237769/value-of-the-us-entertainment-and-media-market/

----
