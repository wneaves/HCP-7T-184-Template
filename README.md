# HCP Young Adult 7T Average Template
This repository provides the average template generated from 184 T1-weighted (T1w) 7T scans, made available by the Human Connectome Project (Van Essen et al., 2013) in the S1200 Release of the original young adult HCP study (February 2017). This template is suitable for group-average analyses.

Additionally, a Jupyter Notebook script is included. This script allows you to search through the HCP Amazon S3 bucket and download the relevant 7T T1w files, enabling you to generate the template yourself. To run the script, you will need [MRtrix3](https://www.mrtrix.org/) installed (brief instructions to run the template generation code are provided in the notebook). The script generates warp files for each dataset, which can then be used to transform the data into the template space.

![example of 184 template](https://github.com/wneaves/HCP-7T-184-Template/blob/main/Example.png)
