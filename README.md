# Assignment_2_Upsampling


Subtask 1: 
Implement a bilateral filter
Implement the Bilateral or the Bilateral Median filter, your choice.
Evaluate the filter on an image of your choice. 
Evaluation:  The Bilateral filter has two parameters, two variances (sigmas), one for the spatial filter (Gaussian, \(w_G\) kernel in the slides), and one for the spectral filter (\(f\) in the slides, also called the range kernel).      
Choose four different levels of sigmas for the spatial and four for the spectral filter.     
Test all combinations, 16 in total, by running the Bilateral filter on the image of your choosing.     
Save the resulting images onto disk.  

Subtask 2: Create a guided filter
Convert a bilateral filter to Guided Joint bilateral filter for guided image upsampling.
Apply the filter to upsample a depth image, guided by an RGB image. (You can use an image pair from a Middlebury stereo dataset, or any of your choice.)

Subtask 3 (Evaluation):

 12 RGB-depth image pairs from at least 2 datasets combined!
    (Tips: e.g., Middlebury, KITTI)
    Extra points for also using your own disparity images from the 1st Assignment.
     
 Synthetic depth generation:
        create downsampled version of ground truth
        add some noise
        decrease resolution (by factor of 4 - 8)
          
