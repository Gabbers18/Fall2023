## Visualizing Children's Word Learning

### Overview
Young children are exceptional learners, especially when it comes to language. By the age of 12 months, they begin producing simple words, and their phonological processing becomes mature around 18 months. From then until the age of five, children acquire an average of 6-7 words per day.

Rather than learning words randomly or primarily through formal education, children acquire vocabulary based on daily interactions and experiences. This lab explores the factors influencing which words children learn and when, using real-world data from the Wordbank database.

### Objectives: 
- Visualize trends across time
- Visualizing relationships between variables
- Discovering Simpson’s paradox via visualizations
 

### **Exercises**  

1. Identify the three most commonly produced words by 18-month-olds. Among the "sounds" category, which sound is least likely to be produced at 30 months?  

2. Plot the learning trajectory of words in the "sounds" category from 16 to 30 months. Use proportion of children producing the word on the y-axis and age on the x-axis. Which word do children know best? Which is learned the fastest from 16 to 25 months, and why might that be?  

3. Plot the learning trajectories for different word categories: "sounds," "games_routines," "body_parts," "animals," "clothing," "people," "pronouns," "connecting_words," "quantifiers," and "helping_verbs." Use proportion of children producing the word on the y-axis and age on the x-axis. Consider using faceting or linetypes for clarity.  

4. List the 10 most and least frequent words in the dataset.  

5. Create a plot showing the relationship between word frequency and the proportion of children producing the word at 24 months. Use log-transformed frequency on the x-axis.  

6. Add a linear trend line to the plot using `geom_smooth(method="lm")`.  

7. Describe the relationship: Is it positive, negative, or non-existent? Is this surprising? What could explain it?  

8. Identify low-frequency word categories that children might hear often despite their low presence in written texts.  

9. Find the most frequent words in categories that are difficult for children to learn (e.g., quantifiers, connecting words). How often do children hear these words in everyday speech?
