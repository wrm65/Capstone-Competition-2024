# Capstone Competition 2024
 Imperial College Business School Capstone Competition 2024
> for the collaborative group

### Uploading your results
> Here are the steps to upload your files, `queries.txt` and `observations.txt`:
> - prefix your files with your student id i.e `484_queries.txt` and `484_observations.txt`
> - copy your files to the appropriate `week number folder` within the `results directory`
> - that's it...Thank you!


### Download the latest results
> You will need to download the following into your `Jupyter environment`:
> - the Jupyter notebook `load_capstone_results.ipynb`
> - the `initial_data directory` which contains the functions' initial inputs and output files (these are `numpy` format files)
> - the `data directory` which contains the students result files (queries and observations - these are plain `text` files)
> - that's it...Thank you!


### View the latest results
> After downloading all the above into your `Jupyter environment`:
> - run the notebook `load_capstone_results.ipynb`
> - the initial data and the students' result data will be merged and stored in the directory `update_data` in `numpy` format files
> - to view your results, run the method `print_student_results` with your `student_id` e.g. loader.print_student_results(484). This will print your results, ordered by week number
> - you can view your results, sorted by function number, by including a `True` argument to the `print_student_results` method e.g. `loader.print_student_results(484, True)`
> - to view the (entire) updated results, run the method `print_results` e.g. `loader.print_results()`
> - the observation results can also be viewed graphically by running the method `plot_observations`. Pass in your `student id` as an argument and your observations will be highlighted on each graph e.g. `loader.plot_observations(484)`
> - run the method `loader.save_results()` to save the results to a `CSV file`
> - there are a collection of other useful functions such as:
> - `get_initial_function_data`
> - `get_data_results`
> - `get_week_list`
> - `get_student_list`
> - Thank you!

### Final Leaderboard Positions

#### - Students Ranking per Function
![Student Ranking](docs/images/leadboard_ranking.jpg?raw=true "Student Ranking")

#### - Students Position per Function with Overall Ranking
![Student Position](docs/images/leadboard_student_1.jpg?raw=true "Student Ranking")


### Graphs showing (up to week 7) the weekly observations for each function

![Graph Functions 1 - 8](docs/images/graph_240228_1934.jpg?raw=true "Functions 1 - 8")

