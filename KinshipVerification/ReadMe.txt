Kinship Verification Dataset

Overview

The Kinship Verificaiton Dataset contains the parents-children images used in the paper "Towards Computational Models of Kinship Verification" (ICIP 2010) by Ruogu Fang, Kevin D. Tang, Noah Snavely and Tsuhan Chen.

There are 143 pairs of parents and children. The parents images are in the folder 'Parents', while the children images are in the folder 'Children'. Each parent image has a corresonding child image with the same index number, e.g. 'Parent_001.jpg' is the parent of 'Child_001.jpg'. 

Terms of Use
Please adhere to the following terms of use of this dataset. 
This dataset is for non-commercial reseach purposes (such as academic research) only. The images are not allowed to be redistributed (do not pass copies of any part of this collection to others, or post any images on the Internet). 

If you use any part of this image collection in your research, please cite the paper below.

People
Ruogu Fang
Kevin D. Tang
Noah Snavely
Tsuhan Chen

Citation
Ruogu Fang, Kevin D. Tang, Noah Snavely, Tsuhan Chen. Towards Computational Models of Kinship Verification. IEEE International Conference on Image Processing, Hong Kong, September 2010 (ICIP '10) 

Bibtex
@inproceedings{fang2010kinship,
 author = "Ruogu Fang and Kevin D. Tang and Noah Snavely and Tsuhan Chen",
 title = "Towards Computational Models of Kinship Verification",
 booktitle = "IEEE Conference on Image Processing (ICIP)",
 year = "2010",
 month = "September",
 address = "Hong Kong, China"
}

Datafiles
The ground truth file "groundtruth.txt" contains one row per face in the collection. It begins with the number of images for parents or children. 
Each row contains the following six tab-separated fields:

ImageName
LeftEyeXCoord
LeftEyeYCoord
RightEyeXCoord
RightEyeYCoord

Note that the left and right eyes are with respect to the viewer, so are opposite the person's point of view. Here X coordinate is the row number , Y coordinate is the column number.