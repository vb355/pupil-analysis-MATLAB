# pupil-analysis-MATLAB
Step 1. For our purpose we obtained video files ".seq". To analyze our video files in MATLAB we need to convert ".seq" to "tiff".

Step 2. Respectively, inside the folder where ".seq" files are located, you should create a folder with the name "tiff". You should indicate the pathway for converted to "tiff" files to this folder.


Step 3. Now, next to the "tiff" folder create a new folder called "test".

Step 4. Take 6-10 tiff files and put it inside folder "test". Usually, 6-10 files are enough to understand whether the chosen contrast value works or not for a particular mouse.

Step 5. Open MATLAB. We are going to utilize the first script that allows us to analyze movies with our data. In the main window open "browse for folder", then, open the folder that has a name "pupil segmentation" -> select folder. In "Current Folder" window click right mouse button -> select "add to path" -> current folder.  Then select "eye_analysis_8_DM_CL8.m".

Step 6. In the new window where the script is located find a green "play" button on the control panel. It is called "run"

Step 7. Click it, then find your folder "test" and select this folder in order to test how applicable your contrast value to obtain the best version of graphs.

Step 8. When you select the folder "test" a window will appear. " please enter a value for contrast adjustment". You can enter different values. I used values from 0.03 to 0.15

Step 9. After MATLAB will be done with the analysis you see the graphs. 

Step 9a. To save what is appeared in the "graph" window (it is better to save it cause it is not saved as a picture automatically by the program). So whenevel you need a picture of a grapf and you did not save it you have to analyze all tiffs for a particular set of videos again).

Step 9b. To save a picture from the window with graphs you  can use File -> save as. Or make a window screenshot.

Step 10. If you satisfied with the appearance of the graph lines, its smoothness, and lack of artifacts, as well as the number of artifacts in general) you can apply intensity of your choice to the main folder.

Step 10a. After step 10, repeat step 9, 9a, 9b.

After you analyzed all tiff files you needed in a folder you should have 3 files besides tiffs in a folder.
"picture"

Step 11. Now we begin analysis of the average of each set of trials. After we will get the average we can compare averages. In my case I had two groups o fmice and compared average data between two groups.

Step 12. We need to start working with the script called "pupil_average_tg"
