This project combines both the use of PostGreSQL and python to perform exploratory data analysis. The project first starts with utilizing PostGreSQL in PGAdmin4 in order to combine multiple tables together into one using the "inner join" feature. Once the ideal table is built, it is carried over into juypter notebook, where python's powerful libraries can be taken advantage of to perform exploratory data analysis and visualize relationships among variables.

PostGreSQL is used to combine 3 tables; the main table containing songs and each of their attributes, a smaller table containing the release dates of each title track, and a smaller table containing all girl and boy groups and their year of debut. Once the ideal table is made, it is brought into juypter notebook, where you can now analyze trends in the attributes over time. You can also analyze trends based on the gender of the group. 

On July 3rd, 2023, the project was updated to include the following changes via a pull request:

  -Used the concept of "mask" to avoid having to manually type index numbers when removing rows by their indexes

  -Created a list containing words that songs should not have, and Used a "For" loop to remove all songs in the databases containing any of the words, rather than     manually removing songs word by word

  -Used a boxplot rather than a scatterplot to get insight on song attributes as a function of time

  -Added more comments on the analysis seem from graphs
