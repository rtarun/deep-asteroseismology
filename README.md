# deep-asteroseismology
Inferring stellar age and rotation period by applying RNNs on Kepler data

Stellar properties from Kepler light curves using Recurrent Neural Networks. There is a lot of information about the mass, age and rotation period of a star in its light curve but our physical models and the tools we use to extract this information are flawed. Perhaps we can do better with RNNs?

Astro Hack Week 2018 project

Original idea and inputs by Ruth Angus

Data source to be worked on:

Red giant stars in the following table:
https://arxiv.org/src/1802.04455v2/anc/Table2.txt

Paper link:
https://arxiv.org/pdf/1802.04455.pdf


Plan is to get all the FIT files for these 16K red giants, normalize them, stitch them together, and then start the RNN analysis. But data. Real world data never be clean and organized. Also, getting all the FIT files hasn't been easy (using kplr+astropy-pyfits packages). Now swtiching to using simulated data, and come back to this at a later point.


Also, just going to leave this diagram here. It's so neat!

!(https://github.com/rtarun/deep-asteroseismology/blob/master/assets/Hertzsprung-Russel_StarData.png)

![picture](assets/Hertzsprung-Russel_StarData.png)
