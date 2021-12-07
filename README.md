# How should you optimize your Pokemon Teams?

###### About us
Gowtham Rajendra (GowthamRajendra)
Ravi Pogaku (Ravi-Pogaku)
Ivan Wang (Ivan-WangJianBin)

## Introduction
  While searching for datasets, this Pokemon dataset caught our attention since we all grew up playing the Pokemon games. So, we decided to analyze this because we all had an interest in it and had some prior knowledge of the data. This helped us easily understand the data and determine how exactly to use the data to our advantage.

### Motivations
  Since we are fans of Pokemon, there were some statistics and information we were interested in such as the best way to assemble a team. To do that, we decided to conduct research on finding strong pokemon by using methods such as finding the strongest type and strongest generation of Pokemon. We also were interested in general trends that existed between statistics of Pokemon. 

### Where did the information come from?
  The dataset we used for our project is called The Complete Pokemon Dataset: Data on more than 800 Pokemon from all 7 Generations by Rounak Banik. This dataset was updated 4 years ago, and as such, it no longer holds true on the claim of being the complete Pokemon dataset since there have been many new updates to Pokemon that were not included in the dataset. The dataset includes information on name, abilities, classification, types, height and weight, stats, type advantages, base happiness, how long it takes to hatch and level up, if they are legendaries, and what generation of Pokemon they are from. This information within the dataset allowed us to discover many trends that many of us did not expect by either comparing them in certain ways or to add them all together to see if there are any trends. While there are certain errors such as missing information or wrong types and abilities, they are in the minority and we have realized the cause of such errors and have managed to fix them during the project.
      insert image here
 
## Discussion
### Does the term “Weigh Down” apply? 
  An interesting finding that we have found during our research is that speed and weight are not correlated in any way. Normally, one would expect that heavier pokemon would be slower than pokemon that weigh close to nothing, but the regression plot that plots the weight (kg) on the y-axis and the speed on the x-axis proves otherwise. It shows that speed is not affected by weight whatsoever. Evidence of this would be how the fastest pokemon weighs more than half of the other pokemon, yet none of the pokemon come close to its speed. Furthermore, the highest dot on the y-axis which represents the heaviest pokemon is still faster than dozens of pokemon that are lighter than it. 
      insert image here
      
### Most common Legendary types?
  Another interesting find would be the primary types of legendary pokemon. Since the average base stat of all types shows that Dragon is the type with the highest stat. We expected that the primary type of many legendaries would be Dragon since the majority of legendary pokemon boasts stats higher than normal pokemon. But, the frequency of primary type for legendary pokemon shows that Psychic is the much more common primary type of legendaries with Dragon only being more common as the secondary typing. While typing orders does not matter, it is still surprising that Dragon is not the primary type for many legendaries.
    insert image here
    insert image here

### Best Type for each generation?
  When we started the research and analysis, we expected the three starter typings of Fire, Water or Grass to be the most effective type to use in every generation. And if they are not, then maybe other popular types such as Psychic, Dark, Fighting, Flying, Electric, or Dragon to be the most effective, but interestingly enough, types that are not as popular as the ones mentioned above came at the top. We did not expect types such as Rock and Ice to end up as the most effective type to use in most generations. The graph shows that using Rock and Ice types throughout multiple generations is the most effective strategy, this is an interesting finding since it allows anyone that looks at the graph to know what kind of Pokemon types they should use if they want an easier time playing in that generation.
        insert image here
        insert image here

## Conclusion
### Reflection
  Throughout this assignment, we have learned many surprising new things that we have never discovered before while playing the games. We first had to clean and filter out any unnecessary data and errors. We then used a combination of different types of graphs depending on the data we needed in order to show the best result. In the end, the data that stood out to us among the many we collected was Speed vs Weight Correlation, the Most common types among legendaries, and the best type for each generation. These three graphs were picked since we all learned something unexpected and new from them.
 
### Refinement
  In this analysis, there were many minor errors such as combining regional variants with their normal counterparts which caused the typings to be incorrect and some values were missing. An improvement for next time would be to have a dataset that differentiates different pokemon forms better and has more data that are useful than ones that we never used such as happiness, classification, etc.

    
