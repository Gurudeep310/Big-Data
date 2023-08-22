Project Title
The project aims to find the total viewers of each TV show aired on the ABC network. We have two CSV files, input1.txt, and input2.txt, containing the data of TV shows and their viewership, respectively. We use PySpark to join the two datasets, filter the ABC network's shows, group them by their names, and find the total number of viewers. Finally, we store the results in a text file named output.txt.

Prerequisites:
Python 3.x
Spark 3.x
findspark module
pandas module
Running the code

Install the necessary modules using the following command:
pip install findspark pandas
Make sure you have Spark installed and set the SPARK_HOME environment variable to the Spark installation directory's path.

Run the PySpark program using the following command:
spark-submit script.py
where script.py is the name of the PySpark file.

After the program runs successfully, check the output.txt file to find the results.

Output Format
The output.txt file contains the following columns:
ShowName: The name of the TV show.
total_viewers: The total number of viewers who watched the show on the ABC network.
Each row in the file is separated by a comma.