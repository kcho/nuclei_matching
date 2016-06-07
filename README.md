# Thalamic segmentation classification

## 2016_05_30


- The connectivity based segmentation of thalamic maps in different subjects varies a lot

- In order to define which thalamic nuclei the output segment represents,

    - Each subject's segmentation maps were registered to MNI space using FNIRT
        
            - Sum of all subjects' segmentation maps were estimated
                
                    - Thresholded ( 90% )
                        
                            - Overlaid with the Talairach atlas
                                
                                        - % of overlap with each Talairach atlas thalamic nuclei is calculated
