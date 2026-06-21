This dataset, named "Data_TomoSAR_Interferogram", is used in the submitted manuscript "Hybrid geometry calibration model-based baseline error compensation of TomoSAR at a small squint angle for forest vertical structure estimation".

The data are provided as a series of MAT files containing four 4-D double-precision arrays. They can be opened and processed using MATLAB. They are the interferogram patches from uncalibrated TomoSAR datasets of Shanghailin and Genhe test areas. Arrays with "Coh" in their names are correlation coefficients, and arrays with "Pha" in their names are wrapped interferometric phases after removing the flat-earth and topographic phases. The description of each array is as follows:

-- Coh_Shanghailin, Pha_Shanghailin: the dimensions of both arrays are [height, width, 11, 12]. They correspond to all interferometric pairs from 12 repeat-pass HH polarization SAR images covering the Shanghailin test area. The number 1 to 12 in the third and fourth dimension corresponded to H4410, H4230, H4260, H4290, H4320, H4350, H4380, H4440, H4470, H4500, H4530, and H4570, respectively. The third dimension represents the master image, and the fourth dimension represents the slave image. For example, the correlation coefficient of the interferometric pair with H4410 as the master image and H4230 as the slave image is given by coh_Shanghailin (:,:,1,2); the phase of the interferometric pair with H4530 as the master image and H4570 as the slave image is given by pha_Shanghailin (:,:,11,12).

-- Coh_Genhe, Pha_Genhe: the dimensions of both arrays are [height, width, 9, 10]. They correspond to all interferometric pairs from 10 repeat-pass HH polarization SAR images covering the Genhe test area. The number 1 to 10 in the third and fourth dimension corresponded to H4820, H4850, H4876, H4905, H4934, H4961, H4991, H5018, H5049, and H5079, respectively. The third dimension represents the master image, and the fourth dimension represents the slave image. For example, the correlation coefficient of the interferometric pair with H4820 as the master image and H4850 as the slave image is given by coh_Genhe(:,:,1,2); the phase of the interferometric pair with H5049 as the master image and H5079 as the slave image is given by pha_Genhe(:,:,9,10).

Any researchers having any questions about our research are welcome to contact: 

Lei Shi (shi.lei@whu.edu.cn), 
Tianyi Song (songtianyi@whu.edu.cn), 
Weidong Sun (widensun2012@whu.edu.cn).
