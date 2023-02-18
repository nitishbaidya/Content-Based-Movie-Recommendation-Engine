# Content Based Movie Recommendation Engine 

Below are the instructions to run the code.

I suggest running the code in Jupyter Notebook with the Anaconda installation.

Additional Installations needed:

- Wordcloud: Run "pip install wordcloud" to install the package. The model does function without the package - you can choose to skip the code that generates the wordclouds.

Running the code:
- Extract the data files directly into the "Data" folder. 
- Run the code from start to end in order.
- Run the code "run_engine()" to start the main function.
- Enter the option for module for recommendations i.e. based on genre/titles/search
- Next:
	- Enter the genre for getting recommendations with a genre. The list of available genres is printed in the previous step
	OR
	- Enter the full movie title for getting recommendations based on a movie title.
	OR
	- Enter the search term for getting recommendations based on search

Make sure to spell the words/title correctly.

Changing the threshold:
- Change the value of the variable "threshold" in the code. Recommended values are: 3 for strictly similar, 5 for mixed, 7 for losely similar movies.
- If the threshold is upated, make sure to rerun the code from the start before running the function "run_engine"

