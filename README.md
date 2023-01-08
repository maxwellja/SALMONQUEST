# SALMONQUEST


I moved from Illinois to Oregon in the summer of 2022, and I was eager to catch salmon on all the ocean-feeding rivers that neighbor my new home. There's one problem, I don't know when salmon are running! In this project, I will answer the following question: 

About when in the year should I go fishing in the Columbia River to have the highest historical probably of catching a salmon for dinner?

To answer this question, I will systematically extract, process, and analyze csv data courtesy of Columbia Basin Research's Columbia River DART dashboard: https://www.cbr.washington.edu/dart/overview. The data counts adult salmon passages from each day in 2022. The data is collected at a variety of salmon ladders - a manmade salmon pathway from a portion of the river below a dam to the portion of the river above the dam - using cameras to count individual fish from the months March through November. During the winter months, salmon are not frequent enough to count.

I will quantify the date range in 2022 with the highest number of adult salmon passages at all the monitored dams along the Columbia river. By quantifying the best time to fish in 2022 I can project when the best time to fish in 2023 will likely occur.

This project is broken up into four parts: Extraction, Cleaning, Analysis, and Presentation. I leverage the pandas library of python for the Extraction, Cleaning, and Analysis portions. I create a visualization with both Excel and Tableau to concisely display my findings and support my conclusion.


CBR Metadata and Glossery: https://www.cbr.washington.edu/dart/metadata/adult.
