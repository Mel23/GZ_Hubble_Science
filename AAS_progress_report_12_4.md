
AAS progress - 04 Dec 2015
=====
### Progress Report - Red Disk Fraction project for 2016 AAS
*Melanie Galloway*

#### The degree of boosting of p_features for the Hubble dat:

A couple of plots were requested to help 1) verify that debiasing the FERENGI p_features values would be best for targeting incompleteness and 2) check that the debiasing procedure is doing what we want it to do.  

First, a look at debiased vs raw p_features:

![Visit GitHub!](https://github.com/Mel23/GZ_Hubble_Science/blob/master/Red_Disk_Fraction/Images/debiased_features_hubble.png)

*Debiased p_features vs uncorrected p_features for all GZ Hubble galaxies. Black are from the correctable region, red are from the uncorrectable region. *

![Visit GitHub!](https://github.com/Mel23/GZ_Hubble_Science/blob/master/Red_Disk_Fraction/Images/best_features_hubble.png)

*'Best' p_features vs uncorrected p_features for all GZ Hubble galaxies. The 'best' value is the debiased value if it is a correctable galaxy. If it is not correctable, the best value is either the 90% confidence lower limit or the uncorrected value, whichever is greater.*

Take-away: Looks good? 

#### Using FERENGI to measure incompleteness in disk fractions

![Visit GitHub!](https://github.com/Mel23/GZ_Hubble_Science/blob/master/Red_Disk_Fraction/Images/all_ferengi_corrected_best.png)

*Incompleteness for all FERENGI galaxies - black are the correctable galaxies, red are uncorrectable. Observed values are the 'best' value - debiased for correctable galaxies, and max(lower limit, raw) for uncorrectable galaxies.*

![Visit GitHub!](https://github.com/Mel23/GZ_Hubble_Science/blob/master/Red_Disk_Fraction/Images/all_ferengi_corrected_debiased.png)

*Incompleteness for all FERENGI galaxies - black are the correctable galaxies, red are uncorrectable. Observed values are the 'debiased' value - clearly uncorrectable galaxies get boosted too high; contaminating our observed poputlation of disks with ellipticals (upper left region in each square).*


