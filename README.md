# UnsedWellsOfLouisiana
 Identifying risks and uses of abandoned and shut-in wells in northern Louisiana.
Project Title
This project is to analyze the Louisiana state database of wells. There are evolving objectives to this. One objective is to determine the likelihood that a well that is not being utilized developing a leak. Furthermore among the objectives is to identify unused wells that could be potential candidates for other activities inluding: water production, disposal, observation, and geothermal energy.

Getting Started
Currently, there are two folders within which some code and data exist. The folder Overall Data_Segmentation contains the code needed to take two databases where both og them can be joined using a key of serial number of the wells. In the particular code here, one databse contains information about well status but it lacks latitude, longitude information. The other one does have the latitude, logitude information. The objective here is to get the latitude and longitude data in the main database and separate wells by their status code and plot them and also store them into two different databases for later use. The second folder "Leak Potential Analysis" takes databases of the format such as the one that is the output of analysis in the Overall Data_Segmentation folder and peforms operations on the wells that have leak risk and estimates that risk and plots it using various methods.

Prerequisites
Only Python and Pandas libraries are needed to run these notebooks. You can try them with other types of files downloaded from the web including, but not limited to, Louisiana Department of Natural Resources.

Built With



Author
Babak Akbari


