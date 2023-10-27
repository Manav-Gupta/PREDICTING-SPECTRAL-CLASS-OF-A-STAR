# PREDICTING SPECTRAL CLASS OF A STAR
This project determines the spectral class of a star (O,B,A,F,G,K,,M) which is based on the size and heat of star according to the H-R diagram. With the help of other features containing different properties of a star, LSTM is employed to classfy the star using the given set of data. LSTM while mostly used for regression can also be employed for classification thus making it a robust machine learning technique used for various applications. 

Dataset : https://www.kaggle.com/deepu1109/star-dataset
This is a dataset consisting of several features of stars.

Some of them are:

Absolute Temperature (in K)
Relative Luminosity (L/Lo)
Relative Radius (R/Ro)
Absolute Magnitude (Mv)
Star Color (white,Red,Blue,Yellow,yellow-orange etc)
Spectral Class (O,B,A,F,G,K,,M)
Star Type (Red Dwarf, Brown Dwarf, White Dwarf, Main Sequence , SuperGiants, HyperGiants)
Lo = 3.828 x 10^26 Watts (Avg Luminosity of Sun)
Ro = 6.9551 x 10^8 m (Avg Radius of Sun)

