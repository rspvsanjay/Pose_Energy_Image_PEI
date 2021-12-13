# Pose_Energy_Image_PEI

The Pose Energy Image (PEI) can be created using uploaded code files which are implimented using MATLAB code.

The Key poses have not been created as given in the related research work using distortion rate. To construct the key pose set the half gait cycle extracted first from each subject the frames are condensed into single image respect to their pose.

Consider you have the normalized silhouette images then to find the Pose Energy Image (PEI) we can follow the code files in the following sequence:

Select_doubble_support_frames.m, halfCycleSelection.m, CountCycleLength2.m, Global_half_Cycle_frames3.m, Pose_Energy_Image.m



The above codes are not exactly match but related to the following research work:

Title: "Gait recognition using Pose Kinematics and Pose Energy Image"
https://www.sciencedirect.com/science/article/pii/S0165168411003392

Title: “Exploiting Pose Dynamics for Human Recognition from Their Gait Signature”
DOI: https://doi.org/10.1007/s11042-020-10071-9

Title: “Gait Recognition in the Presence of Co-variate Conditions”
DOI: https://doi.org/10.1016/j.neucom.2021.04.113 

Title: “Reduction of Covariate Factors from Silhouette Image for Robust Gait Recognition” 
DOI: https://doi.org/10.1007/s11042-021-10941-w 
