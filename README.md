# C(3P)-CO2 cross-sections - raw data (alpha; pre-publication version)
by Marko Gacesa (marko.gacesa@ku.ac.ae), Aug 8 2023

Includes: scattering cross section data after post-processing molscat files.   

The files are distributed under GNU General Public License v3.0 and include no warranty or guarantees of any kind. The results are release 'as is' and no support is provided. The author is not liable for any loss or damages resulting from using the datasets. We do not promise (but we will try!) to answer any questions related to this dataset nor to prepare different data products for you. 

Please cite these datasets in academic publications either as a hyperlink to this GitHub depo or the related Zenodo doi.  

File & directory structure:
---------------------------
C-CO2_table_integral-CS_1pes.dat       -> integral elastic cross sections for C+CO2(j=0) -> C+CO2(j'=0)
C-CO2_table_momentum-transfer-CS_1pes  -> momentum transfer cross sections; same states as above
13C-CO2_table_integral-CS_1pes.dat       -> as above, for 13C-CO2
13C-CO2_table_momentum-transfer-CS_1pes  -> as above, for 13C-CO2

./12C-CO2_CSs/ -> state-to-state cross sections for 41 collision energy points (from 0.029 eV to 5 eV). Single  potential energy surface. See the publication for details.

./12C-CO2_DCS/ -> differential cross sections (elastic and total = elastic+inelastic) given as a function of the scattering angle for 41 collision energies, as above. This is a single-surface scattering calculation without any couplings to excited electronic states included. 

./13C-CO2_CSs/ -> As above, for 13C-CO2
./13C-CO2_DCS/ -> As above, for 13C-CO2
