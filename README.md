
# EMIP-Toolkit

EMIP Toolkit: A Python Library for Customized Post-processing of the Eye Movements in Programming Dataset

[Full Text](https://www.researchgate.net/publication/350485560_EMIP_Toolkit_A_Python_Library_for_Customized_Post-processing_of_the_Eye_Movements_in_Programming_Dataset).


# Please Cite: 
Naser Al Madi, Drew T. Guarnera, Bonita Sharif, and Jonathan I. Maletic.2021. EMIP Toolkit: A Python Library for Customized Post-processing of the Eye Movements in Programming Dataset. In ETRA ’21: 2021 Symposium on Eye Tracking Research and Applications (ETRA ’21 Short Papers), May25–27, 2021, Virtual Event, Germany. ACM, New York, NY, USA, 6 pages. https://doi.org/10.1145/3448018.3457425


# Features:
The toolkit is specifically designed to make using the EMIP dataset easier and more accessible by providing the following functions:
 
 
 - Parsing raw data files from the EMIP dataset into Experiment, Trial, and Fixation containers.
    
 - Customizable dispersion-based fixation detection algorithm implementation according to the manual of the SMI eye tracker used in the data collection.
   
 - Raw data and filtered data visualizations for each trial.
    
 - Performing hit testing between fixations and AOIs to determine the fixations over each AOI.
        
 - Customizable offset-based fixation correction implementation for each trial.
    
 - Customizable Areas Of Interest (AOIs) mapping implementation at the line level or token level in source code for each trial.
    
 - Visualizing AOIs before and after fixations overlay on the code stimulus.
    
 - Mapping source code tokens to generated AOIs and eye movement data.
    
 - Adding source code lexical category tags to eye movement data using [srcML](https://www.srcml.org/). srcML is a static analysis tool and data format that provides very accurate syntactic categories (method signatures, parameters, function names, method calls, declarations and so on) for source code. We use it to enhance the eye movements dataset to enable better querying capabilities. 


# Examples and tutorial:
The Jupyter Notebook file "EMIP Toolkit Examples.ipynb" contains examples and a tutorial on using the EMIP Toolkit. The file describes the required file structure and raw EMIP files and metadata from http://emipws.org/.


# Corrected Dataset:
The directory “Corrected EMIP Dataset” includes our second contribution of a filtered, corrected, and processed version of the EMIP dataset.


# Requirements:
numpy==1.18.1

pandas==1.0.1

matplotlib==3.1.3

Pillow==8.1.2

# Original project:
https://github.com/nalmadi/EMIP-Toolkit.git
