# BSc_Thesis_SLAM_MerelDas_s1019419
This repository contains all the SLAM maps and written code by Merel

In the 'SLAM maps' folder, all maps can be found that were generated. They are divided by variable. The maps are saved in .pgm format, these can be opened with many file viewer apps. For example 'File Viewer Plus 4'. For the variable 'laser noise', two extra folders are included. The folder 'cut' contains the images that were cropped by hand. The folder 'binary' contains these same image after binarization.

In the 'scripts' folder, several Bash scripts can be found. The scripts 'practiceScript', 'recoverScript', 'slipScript' and 'slipRecover' were used to launch the mapping process with Gazebo-ROS for the different variables.  

The 'similarity' folder, contains a Jupyter notebook and a Bash script called 'similarityScript'. The Bash script runs the similarity metric on all binarized images and saves the scores in a file called similarities.txt. The Jupyter notebook contains code to resize and binarize cropped images, as well as code to add together the similarity scores to compute the mean and sttdevs of the scores.

The 'worlds' folder contains all the .world files that contain the layouts. These can be used in combination with the launch scripts in the 'scripts' folder to load the layouts and robot into Gazebo. 
