The joint attention (between two persons) dataset of Huang, Yifei, et al., "Temporal Localization and Spatial Segmentation of Joint Attention in Multiple First-Person Videos," Proceedings of the IEEE International Conference on Computer Vision Workshop, 2017.

This dataset involves four different experiment settings:
1) sbs: side-by-side 
2) f2f: face-to-face
3) big: big head motion
4) small: small head motion
as explained in the paper.

Every subject pair is indicated by the last two characters of the .tar.gz file name.
For example, 'f2f_big_cl' and 'f2f_big_lc' are two file folders containing data/label of one subject pair recorded in the setting of 'f2f_big'. 'c' and 'l' are the first letter of two subjects' last name. 

Gaze position and joint attention ground truth are provided as .mat files, synchronized with frame number. Note that the joint attention ground truth file is the same for each paired videos.

Segmentation masks are in the folder 'SegGT'.