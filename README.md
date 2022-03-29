# Around-The-Pipe-Audio-Based-Water-Tracker-for-Home-Residents

Water is one of the most necessary resources within an average household that cannot be quantitatively tracked on a regular basis. There are no methods to this without interfering with the pipeline and flow of water itself. This research presents a revolutionary approach that utilizes audio to measure the amount of water going through a household pipe at any given time with supervised machine learning models. First, different amounts of water were run throughout residential homes with a microphone mounted around the pipe. The output of the microphone is converted into a series of vibrations measured in decibels.  The microphone was tested on seven different pipes in 7 different homes to decrease the data bias. It outputs the string of decibel values with a micro-computing device connected to it.  The amount of water and received audio is documented into a CSV file with over 100 data points. The data was imported into the Jupyter Notebook and the features (water amount, range of decibels, size of pipe) were scaled and the dataset was split into training and testing subsets at a 70/30 ratio in order to assess the model’s accuracy. Neural Networks, K-Nearest Neighbors, Random Forest, Linear Regression, and Logistic Regression were the five models being used. After all the models were trained and edited to improve hyperparameters, they were compared by testing the data, Neural Networks ended up with the highest classification accuracy at 94.6% as reported by ROC methods.
<br><br>
Video Presentation: https://www.youtube.com/watch?v=SY87T37Aa1w
<br><br>
Original Paper: https://www.researchsquare.com/article/rs-1328449/v1
<br><br>
Official Publication: https://opastonline.com/open-access/around-the-pipe-audio-based-water-tracker-for-home-residents.pdf
<br><br>
Code: This includes original data and funtional neaural network for the data. 
