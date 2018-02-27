# dicom-load
File extension agnositic script for loading DICOM files into MATLAB.

## Usage
```
function [imag_vol, path, FileNames] = DICOM_Load(filename_extension);
%% A funtion of read in DICOM Files
% Written by Zackary I. Cleveland 02/26/2018
% 
% Input:    filename_extension: extension of file name, defaults to .dcm
%                               Note, must be a string variable.
%
% Output:   imag_vol:   2D or 3D image output
%           path:       pathway of file containing source data
%           FileNames:  names of files used to generate volume
%%
%% Select files to 2D image or 3D image output
```
