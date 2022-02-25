# experimental_data_preprocessing

# Create_tform.m
Estimate the transform matrix between x and y channels. 
The example data: 
data151_xch is thunderstorm estimation results for beads in x channel. 
data151_ych is thunderstorm estimation results for beads in y channel. Note, we don’t have to flip the y channel during the thunderstorm process

# crop_save_image.m
crop and save tiff images based on estimated tform.m
This code allows separate a big FoV into multiple small FoVs.


# background_estimation_by_subtruct_SMs.m
Estimate the background by subtract pixels with SMs. Similarly, thunderstorm estimated results are used to determine the position of SM for subtracting.
