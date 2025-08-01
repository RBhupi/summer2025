# Daniel Wefer - Weekly Logs

### Week 1

----------------------------------------------
 - completed all mandatory onboarding tasks/training
 - set up the python environment on my lab computer
 - located and downloaded ceilometer data for my project
 - made some basic time-series plots exploring the data
 - researched previous PBLH detection work and possible edge detection algorithms for my project
----------------------------------------------

### Week 2 

----------------------------------------------
 - experimented with extracting and plotting multiple scales of 2d trous wavelet transforms
 - implemented Sobel, Canny, and Lagrangian edge detection algorithms on raw ceilometer data
 - experimented with thresholding and extracting edges from the remaining smoothed image after multiple wavelet scales were extracted
 - toured ATMOS facility
 - attended Eddy Covariance workshop
----------------------------------------------

### Week 3

----------------------------------------------
 - got set up on gce compute
 - implemented vertical and horizontal wavelet transforms and experimented with adding different quantities of each for edge detection
 - implemented OTSU automated thresholding then applied edge detection to the results
 - Tested methods for removing noise
 - created a clean script to run these steps on multiple cases and save the result as a netCDF
 - ran the script on 10 days of ceilometer data
----------------------------------------------

### Week 4

---------------------------------------------
 - Implemented 3-hour windows for PBLH detection
 - Used image labeling to separate bounded regions
---------------------------------------------

### Week 5

---------------------------------------------
- Developed functions to detect precip, fog, and clouds
- Used these to create a "clear air" flag
---------------------------------------------

### Week 6

---------------------------------------------
- Handled nans in the data
- removed noisy artifacts left by the automated OTSU thresholding
- Ran the script and created figures for CROCUS IOP days and the May 16 dust storm day
---------------------------------------------

### Week  7

---------------------------------------------
- Began work on my poster
- developed figures for my poster
---------------------------------------------

### Week 8

---------------------------------------------
- Completed Poster
- began work on project report paper
---------------------------------------------

### Week 9

---------------------------------------------
- Turned code into an open source python package: https://Github.com/DanielWefer/ceil-feature-detection
- Completed paper
---------------------------------------------

### Week 10

---------------------------------------------
- Presented at CELS and Learning On the Lawn
- Finished up other mandatory deliverables
---------------------------------------------
