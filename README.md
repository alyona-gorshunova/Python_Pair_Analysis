# Python Pair Analysis

There's a file containing purchase data from a grocery store, including purchase IDs, item names and quantity. Your task is to find out which pairs of items were purchased most of all, i.e. you should look for data patterns that would benefit the store. Write a function that returns a table containing top 5 pairs of purchased items.

This function first loads the purchase data from the file. It then sorts the data by the 'id' and 'Товар' columns. Next, it groups the data by 'id' and applies a lambda function to generate all pairs of items for each 'id'. The pairs are then counted and sorted in descending order by their frequency. The top 5 pairs are printed.
