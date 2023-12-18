# STSA-Toolkit

Below are the steps for installing and guidelines for using the STSA toolkit. 

Step 1: Download Toolkit

Step 2: Install Toolkit

1. Open MATLAB (the app should work on most versions, but has not been tested on versions before MATLAB 2021a)
2. Click the apps tab at the top of the MATLAB interface.
3. Click the "install app" button under the apps toolbar.
4. Select the STSA Toolkit MATLAB app installer file that you downloaded in Step 1 and click install in the window that appears.
5. Click the "Install" button

Step 3: Using the toolkit

The STSA toolkit is designed to make the process of calculating the spatiotemporal index and non-linear alternatives (FDA/DTW indicies of amplitude and temporal variability) as easy as possible. 

1. **Running the toolkit:** Once the app has been installed you should be able to access it by searching your apps in the toolbar at the top. 
2. **Calculating Stability Measures:** Once the app is open simply click the select file button and choose one of the files you want to analyze. The app will then select all other files of the same format within that folder and calculate the STI across all found repetitions.
Note 1: Designed for data that has already been parsed into seperate files for each repetition. Kinematic data should be organized vertically (1 row per time point) and the column you wish to analyze must be specified.
Note 2: STI is calculated by default, click the FDA and DTW checkboxes if you want those analyses run as well (note take longer to run and the app may take a minute to run with these options selected).
3. **View / Write Results:** Plots depicting the analysis are displayed in the center pane and the calculated STI values are displayed on the write. If you would like to compile these results into a spreadsheet with other participants, you can use the "Write Data" button in the bottom right to write the results to the specified file address. By default this appends the data to the bottom of the specified file.
Note: Repeatedly pressing this button will add repeated rows to the specified file.


**Viewiing individual repetitions** Using the arrows in the center pannel you can navigate through the individual repetitions being analyzed. The selected repetition will be highlighted in the display plots. For audio data, you can use the play button to listen to the selected repetition. The app will also display the delta STI value which reflects how much the addition of the selected changes the STI value. Large positive values in this measure indicate outlying repetitions that may be skewing the analysis. 

 
