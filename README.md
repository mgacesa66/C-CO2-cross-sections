# C-CO2_cross-sections - data only (beta release)

Marko Gacesa (marko.gacesa@ku.ac.ae), April 2021

Raw scattering cross section data -- preliminary.

The files are distributed under GNU General Public License v3.0 and include no warranty or guarantees of any kind. The results are release 'as is' and no support is provided. The authors are not liable for any loss or damages resulting from using the datasets. We cannot promise (but we will try) to answer any questions related to this dataset nor to prepare different data products for you.

Please cite this work as a hyperlink to GitHub depo. The results will be published soon (Apr 3 2021). 


Gacesa, Marko (2021). O(3P)+CO_2 scattering cross sections at superthermal collision energies for planetary aeronomy: Raw data pre-release (Version v0.9-beta) [Data set]. Zenodo. http://doi.org/10.5281/zenodo.3256699


File structure:
--------------
C-CO2_table_integral-CS_1pes.dat       -> integral elastic cross sections for C+CO2(j=0) -> C+CO2(j'=0)
C-CO2_table_momentum-transfer-CS_1pes  -> momentum transfer cross sections; same states as above

./CSs_1pes/ -> state-to-state cross sections for 41 collision energy points (0.029-5 eV). Statistically weighted over three potential energy surfaces. See the publication for details.

./DCS_1pes/ -> differential cross sections (elastic and total = elastic+inelastic) given as a function of the scattering angle for 41 collision energies, as above. This is a single-surface scattering calculation without any couplings to excited electronic states included. 

./DCS_inelastic_3pes/ -> differential cross sections, state-to-state (ji->jf) with kinetic energy transfer Te(ji,jf) to the target rotational state ji calculated using a simple kinematic model (see the article). 
