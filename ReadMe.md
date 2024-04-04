
# Spatio-Temporal Image Encoding


This repository contains the implementation of the Spatio-Temporal Image Encoding (STIE), in order to perform Online Human Activity Recognition using 3D skeletons. This method encodes a sequence of 3D skeletons into an image, while preserving both spatial and temporal dependencies. 

Our paper can be found at:

[Human Activity Recognition: A Spatio-temporal Image Encoding of 3D Skeleton Data for Online Action Detection](https://www.researchgate.net/publication/358597221_Human_Activity_Recognition_A_Spatio-temporal_Image_Encoding_of_3D_Skeleton_Data_for_Online_Action_Detection)

If you use or build on our work, please consider citing us:

```
@conference{visapp22,  
author={Nassim Mokhtari. and Alexis Nédélec. and Pierre {De Loor}.},  
title={Human Activity Recognition: A Spatio-temporal Image Encoding of 3D Skeleton Data for Online Action Detection},  
booktitle={Proceedings of the 17th International Joint Conference on Computer Vision, Imaging and Computer Graphics Theory and Applications (VISIGRAPP 2022) - Volume 5: VISAPP},  
year={2022},  
pages={448-455},  
publisher={SciTePress},  
organization={INSTICC},  
doi={10.5220/0010835800003124},  
isbn={978-989-758-555-5},  
issn={2184-4321},  
}
```


## Dataset
Before running our code, please unzip the archive **data.zip** provided in this repo. This archive contains skeleton data and sequence labels from the [Online Action Detection dataset](https://www.icst.pku.edu.cn/struct/Projects/OAD.html).

**note:** If you are using your own dataset, please consider adjusting the *load_data_file()* function.

## Usage
You can start the encoding using the default parameters by running the STIE.py from the command line :

	python ./STIE.py

Several parameters can be used to aduste the encoding according to your needs. You can find more details about these parameters using :

	python ./STIE.py --help

## Encoded Sequence
![Encoded Sequence exemple](https://github.com/nassimmokhtari/STIE/blob/main/images/proposition_1.png)


## Real time detection
![Real time usage exemple](https://github.com/nassimmokhtari/STIE/blob/main/images/drinking.jpg)


