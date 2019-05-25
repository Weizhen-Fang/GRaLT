# GRaLT
## GRaLT:Global Reservoir and Lake Training database
All the reservoir and lake samples were clipped from a one-year-collection of Landsat 8 images of year 2017. Table 1 shows the characteristics of GRaLT. 

| Name          | Band Combination                                                                       | Resolution (m) | Number of training samples | Number of testing samples |
|---------------|---------|----------------|----------------------------|---------------------------|
| Band all      | Coastal \ Blue \ Green \ Red \ NIR \ SWIR 1 \ SWIR 2 \ Pan \ Cirrus \  TIRS 1 \ TIRS 2 | 30             | 3040                       | 760                       |
| Band 543      | Green \ Red \ NIR                                                                      |
| Band 654      | Red \ NIR \ SWIR 1                                                                     |
| Water Contour | MNDWI > 0                                                                              |
| Band 8        | Pan                                                                                    | 15             |
| Pan 654       | Red \ NIR \ SWIR 1                                                                     |




Six kinds of data combinations were tested, including Band all, Band 543, Band 654, and Water Contour (the pixel values of the Modification of Normalized Difference Water Index (MNDWI) that are larger than 0 are set to 1, and the others are set to 0) with 30-metre resolution, and Band 8 and Pan 654 with 15-metre resolution. After random selection, there were 1520 reservoirs and 1520 lakes in the training dataset and 380 reservoirs and 380 lakes in the testing dataset. 
