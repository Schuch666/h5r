# h5r
Repository for the Interface to HDF5 Files in R

# INSTALATION STEPS (tested for R 3.5.1)

export HDF5_HOME=/pach/to/HDF5/installation_root/

wget https://codeload.github.com/Schuch666/h5r/zip/refs/heads/master

mv master h5r-source.zip

unzip h5r-source.zip

R CMD INSTALL --configure-args="--with-hdf5=${HDF5_HOME}" h5r-master´
