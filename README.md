The aim of the project is to detect faults in electrical transimission system and classify the fault based on current and voltage measurment.

After analyzing the fault types shown in the file it was found that the majority of the faults are 3 phase faults, where they make 30% of the faults.
The other types of the faults, each make 20% of the faults occuring on the transimission line. Finally, it was found that 20% of the faults occuring on phase A only, while 40% faults includes phase A. Suggesting an issue related to phase A of the transimmission line

I used the following libraries in my project:
  1- Pandas to read CSV file, wrangle the data, and perform exploratory analysis
  2- matplotlib and seaborn for data visualization and as part of data exploratory analysis.
  3- Sklearn to build the classification model and to measure the model accuracy.

There are two files that can be found in this reposetiry: the data CSV file that contains all the current and voltage measurement, and jupyter notebook where the data analysis and the classification model is built.

The data was obtained from Kaggel website, from the following link:
  https://www.kaggle.com/esathyaprakash/electrical-fault-detection-and-classification
