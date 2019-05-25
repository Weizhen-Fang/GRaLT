# GRaLT
## GRaLT:Global Reservoir and Lake Training database
All the reservoir and lake samples were clipped from a one-year-collection of Landsat 8 images of year 2017. Table 1 shows the characteristics of GRaLT. 

<table border=0 cellpadding=0 cellspacing=0 width=794 style='border-collapse:
 collapse;table-layout:fixed;width:597pt'>
 <col width=72 style='width:54pt'>
 <col width=226 style='mso-width-source:userset;mso-width-alt:7232;width:170pt'>
 <col width=106 style='mso-width-source:userset;mso-width-alt:3392;width:80pt'>
 <col width=204 style='mso-width-source:userset;mso-width-alt:6528;width:153pt'>
 <col width=186 style='mso-width-source:userset;mso-width-alt:5952;width:140pt'>
 <tr height=40 style='height:30.0pt'>
  <td height=40 class=xl6522915 width=72 style='height:30.0pt;width:54pt'>Name</td>
  <td class=xl6522915 width=226 style='width:170pt'>Band Combination</td>
  <td class=xl6522915 width=106 style='width:80pt'>Resolution (m)</td>
  <td class=xl6522915 width=204 style='width:153pt'>Number of training samples</td>
  <td class=xl6522915 width=186 style='width:140pt'>Number of testing samples</td>
 </tr>
 <tr height=60 style='height:45.0pt'>
  <td height=60 class=xl6622915 width=72 style='height:45.0pt;width:54pt'>Band
  all</td>
  <td class=xl6622915 width=226 style='width:170pt'>Coastal \ Blue \ Green \
  Red \ NIR \ SWIR 1 \ SWIR 2 \ Pan \ Cirrus \<span
  style='mso-spacerun:yes'>&nbsp; </span>TIRS 1 \ TIRS 2</td>
  <td rowspan=4 class=xl6722915 width=106 style='border-top:none;width:80pt'>30</td>
  <td rowspan=6 class=xl6722915 width=204 style='border-bottom:1.0pt solid black;
  border-top:none;width:153pt'>3040</td>
  <td rowspan=6 class=xl6722915 width=186 style='border-bottom:1.0pt solid black;
  border-top:none;width:140pt'>760</td>
 </tr>
 <tr height=20 style='height:15.0pt'>
  <td height=20 class=xl6622915 width=72 style='height:15.0pt;width:54pt'>Band
  543</td>
  <td class=xl6622915 width=226 style='width:170pt'>Green \ Red \ NIR</td>
 </tr>
 <tr height=20 style='height:15.0pt'>
  <td height=20 class=xl6622915 width=72 style='height:15.0pt;width:54pt'>Band
  654</td>
  <td class=xl6622915 width=226 style='width:170pt'>Red \ NIR \ SWIR 1</td>
 </tr>
 <tr height=40 style='height:30.0pt'>
  <td height=40 class=xl6622915 width=72 style='height:30.0pt;width:54pt'>Water
  Contour</td>
  <td class=xl6822915 width=226 style='width:170pt'>MNDWI &gt; 0</td>
 </tr>
 <tr height=20 style='height:15.0pt'>
  <td height=20 class=xl6622915 width=72 style='height:15.0pt;width:54pt'>Band
  8</td>
  <td class=xl6622915 width=226 style='width:170pt'>Pan</td>
  <td rowspan=2 class=xl6622915 width=106 style='border-bottom:1.0pt solid black;
  width:80pt'>15</td>
 </tr>
 <tr height=21 style='height:15.75pt'>
  <td height=21 class=xl6922915 width=72 style='height:15.75pt;width:54pt'>Pan
  654</td>
  <td class=xl6922915 width=226 style='width:170pt'>Red \ NIR \ SWIR 1</td>
 </tr>



Six kinds of data combinations were tested, including Band all, Band 543, Band 654, and Water Contour (the pixel values of the Modification of Normalized Difference Water Index (MNDWI) that are larger than 0 are set to 1, and the others are set to 0) with 30-metre resolution, and Band 8 and Pan 654 with 15-metre resolution. After random selection, there were 1520 reservoirs and 1520 lakes in the training dataset and 380 reservoirs and 380 lakes in the testing dataset. 
