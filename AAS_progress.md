AAS progress - 17 Nov 2015
=====
### Progress Report - Red Disk Fraction project for 2016 AAS
*Melanie Galloway*

#### Background:

Continuing Tom Melvin's preliminary work at Portsmouth, I will be using the GZ:Hubble debiased catalog to study the evolution of the fraction of red disks (red disks / all disks) from redshift z=1.0 to z=0.2. 



#### The Sample

I begin with a sample of 84,350 galaxies from the COSMOS field which were classified in GZH. Of these, 70,198 had k-corrected colors and magnitudes in the UltraVISTA catalog. The number of these galaxies within the redshift range of interest ( 0.2 < z < 1.0 ) is 52,707. 

#### Surface Brightness + Redshift effects on p_features


![Visit GitHub!](https://github.com/Mel23/GZ_Hubble_Science/blob/master/Red_Disk_Fraction/SB_vs_redshift.png)

*Fig. 1: Surface brightness (MU_HI parameter from Griffiths et al. 2012) vs. redshift for 70,198 COSMOS galaxies in GZH and UltraVISTA. Galaxies between 0.2 < z < 1.0 will be considered for analysis of red disk fraction; a surface brightness cut is still TBD.*

T. Melvin originally applied an evolving magnitude cut on the sample, as shown by the red boxed region in Figure 2. This region was selected by identifying the region which did not appear to be biased to low values of p_features; that is, the region in which GZ users were reliably able to identify disk galaxies. This cut is used for the inital analysis of red disk fraction presented at the end of this document. 

![Visit GitHub!](https://github.com/Mel23/GZ_Hubble_Science/blob/master/Red_Disk_Fraction/mag_p_features.png)

*Fig. 2: R band magnitude vs redshift for 70,198 COSMOS galaxies in GZH and UltraVISTA. Colors represent the average p_features value for galaxies in each bin; bins with fewer than 50 galaxies are masked. Left: p_features are the weighted (but uncorrected) values; low brightness and high redshift galaxies are biased to low values of p_features. The red boxed region was derived by T. Melvin, which identifies the region of M(R)-z space in which GZ users can reliably identify disk galaxies. Middle: This plot only shows the 'correctable' galaxies identified with the FERENGI data, and the colored p_features are the debiased values. These are biased to high p_features values especially at high redshift and low brightness. Right: the best p_features value is debiased if the galaxy is 'correctable,' the lower limit if it is 'uncorrectable,' and weighted if neither. 

The FERENGI analysis showed that surface brightness also has a strong effect on classifications; a surface brightness cut then may be necessary either instead of, or in addition to, a magnitude cut. Whether the value of this cut will be flat or dependent on redshift is still being discussed. 

Below is a plot of average p_features values in bins of surface brightness and redshift, with an interesting result: At low redshifts, the data is biased toward high value of p_features at high surface brightness, which is expected. However, at high redshifts, it is the dimmer galaxies which have higher average values of p_features. This effect is present with both the uncorrected and corrected data, indicating this may be a physical trend - are dimmer galaxies more likely to be disks at high redshift? Are brighter galaxies more likely to be disks at low redshift? The second effect is explainable by the usual bias, but the former effect is opposite.  

![Visit GitHub!](https://github.com/Mel23/GZ_Hubble_Science/blob/master/Red_Disk_Fraction/mag_SB_p_features.png)

*Fig. 3: Surface brightness vs redshift for 70,198 COSMOS galaxies in GZH and UltraVISTA. Colors represent the average p_features value for galaxies in each bin; bins with fewer than 50 galaxies are masked. Left: p_features are the weighted (but uncorrected) values. Middle: This plot only shows the 'correctable' galaxies identified with the FERENGI data, and the colored p_features are the debiased values. These are biased to high p_features values especially at high redshift and low surface brightness. Right: the best p_features value is debiased if the galaxy is 'correctable,' the lower limit if it is 'uncorrectable,' and weighted if neither.*

#### A look at images 

Here are 16 randomly selected images of galaxies in the extreme regions of the surface brightness - redshift plot:

![Visit GitHub!](https://github.com/Mel23/GZ_Hubble_Science/blob/master/Red_Disk_Fraction/lowz_lowSB.png)

*Fig. 4: Low redshift, low surface brightness*

![Visit GitHub!](https://github.com/Mel23/GZ_Hubble_Science/blob/master/Red_Disk_Fraction/lowz_hiSB.png)

*Fig. 5: Low redshift, high surface brightness*

![Visit GitHub!](https://github.com/Mel23/GZ_Hubble_Science/blob/master/Red_Disk_Fraction/hiz_lowSB.png)

*Fig. 6: High redshift, low surface brightness*

![Visit GitHub!](https://github.com/Mel23/GZ_Hubble_Science/blob/master/Red_Disk_Fraction/hiz_hiSB.png)

*Fig. 7: High redshift, high surface brightness*

Upon viewing the images, it seems the trend at high redshift is driven by the fact that the high surface brightness galaxies are small and centrally concentrated - so either very bulge-dominated disks or actual ellipticals, which both tend to obtain low p_features values by users. 

Input desired from the team: discussion on whether magnitude cut, surface brightness cut, or both is appropriate for this project. 

#### Isolating Red/Passive Disks - color-color plot or color-magnitude? 

Right now I'm exploring which method is best for separating red, passive disk galaxies. Below are plots of various options; I'm hoping to  gain insight from a literature search and GZ team input for what method is most appropriate / optimal. 


![Visit GitHub!](https://github.com/Mel23/GZ_Hubble_Science/blob/master/Red_Disk_Fraction/color_mag_plot.png)

*Fig. 8: NUV - R vs R for 11,139 galaxies, after T. Melvin magnitude cut described above was applied. Colors represent the average value of p_features,best in each bin; bins with fewer than 20 galaxies are masked. Blue lines indicate the separation of red sequence and blue cloud derived by T. Melvin.*

![Visit GitHub!](https://github.com/Mel23/GZ_Hubble_Science/blob/master/Red_Disk_Fraction/color_color_plot.png)

*Fig. 9: NUV - R vs R - J for 11,139 galaxies, after T. Melvin magnitude cut described above was applied. Colors represent the average value of p_features,best in each bin; bins with fewer than 20 galaxies are masked. *


#### Preliminary results using 11,139 galaxies using T. Melvin's magnitude cut and red sequence separation

![Visit GitHub!](https://github.com/Mel23/GZ_Hubble_Science/blob/master/Red_Disk_Fraction/disk_fraction_p_bins.png)


*Fig. 10: red galaxies / all galaxies vs redshift, where only galaxies with p_features in the range specified in the title of each are shown; ie the upper left plot should be red ellipticals / all ellipticals, the lower right should be red disks / all disks, with some mixing of morphologies in between. Red: The cut is made based on the weighted p_features value; hence the first plots are likely contaminated by disks. Green: The cut is made based on the debiased value of p_features, and only considered 'correctable' galaxies. This represents the most accurate value of p_features, so contamination in any bin is minimal. Blue: the cut is made based on the best value of p_features for the whole sample, so debiased if correctable, lower limit if uncorrectable, and weighted if neither.*

