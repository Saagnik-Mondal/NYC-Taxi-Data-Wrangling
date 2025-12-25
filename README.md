## Dataset Used
NYC Taxi Trip Duration Dataset from Kaggle
File used: train.csv
The dataset contains information about taxi pickup and drop-off times, passenger count, and trip duration.

## What I Did in This Project
1. Loaded the Data
Loaded the dataset into a Jupyter Notebook
Checked the number of rows, columns, and data types
2. Explored the Data
Looked at the first few rows
Focused on important columns like pickup time, drop-off time, passenger count, and trip duration
3. Cleaned the Data
Converted pickup and drop-off times to datetime format
Removed rows with:
Invalid passenger counts
Very short or very long trip durations
Made sure the data had no obvious errors
4. Created New Features
Extracted pickup hour
Extracted pickup day of the week
Converted trip duration into minutes
5. Analyzed the Data
Found how many trips happen each hour
Calculated average trip duration by hour
Counted trips per day
6. Visualized the Data
Plotted trips by hour of the day
Plotted passenger count distribution
Visualized trip duration by hour
7. Insights
Taxi trips are more frequent during peak hours
Most trips have 1 or 2 passengers
Trip durations are usually short and consistent
Tools Used
Python
Pandas
Matplotlib / Seaborn
Jupyter Notebook
