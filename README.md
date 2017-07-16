# SNLC
This is the MATLAB implementation of the registration-based approach to sensor network localization using clique described in the following paper: 
[1] R. Sanyal, M. Jaiswal, and K. N. Chaudhury, "On a Registration-Based Approach to Sensor Network Localization", Accepted in IEEE Transactions on Signal Processing. 
If you find SNLC useful in your work, please cite the paper. 
Authors: Rajat Sanyal and Kunal Narayan Chaudhury.

Date: July 2017.

Execute the file Demo.m to see how SNLC works on a random geometric graph. You have to add SNLC folder and subfolders to your current MATLAB path.

Please report any bug to sanyalrajat91@gmail.com.

To run the software:

================================================================== 

(1) Sensor network localization: 
[XEST,Time] = SNLC(DD,Xa,d)

%% Input: 
% DD: Distance information (a square matrix of size N+K). (Top NxN block denotes the inter-sensor distances.) 
% Xa: Location of the anchors (a matrix of size dxK). (Use [ ], if there is no anchor.) 
% d: The dimension of the space where the nodes are embedded.

%% Output: 
% XEST: Estimated sensors locations using the proposed algorithm. 
% Time: Run-time.

================================================================== 

Notations:

N: The number of sensors. 
K: The number of anchors.

==================================================================
