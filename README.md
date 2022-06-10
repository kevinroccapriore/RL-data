# RL-data

This data are scanning transmission electron microscopy (STEM) images whose contrast comes from high angle annular dark field (HAADF) scattering as well as medium angle annular dark field (MAADF).
The specimen is single layer graphene (courtesy Ondrej Dyck), placed on a Protochips TEM grid which allows to rapidly heat the material upwards of 1200 C, which is primarily to reduce contamination from the electron beam.
There are also various single dopant atoms scattered throughout - silicon naturally is present, but there may also be chromium atoms that were very lightly evaporated.

The electron beam in the STEM, which is generally used to image the specimen, can also be used to modify the structure - i.e., move dopant atoms around the surface and into vacancy sites, or even knock out individual carbon atoms, which can depend on accelerating voltage of the beam.
This data then consists of sets of the following:
The purpose of this data is to utilize reinforcement learning (RL) to explore and ultimately learn the rules of the dynamics of single dopant atom movement due to various characteristics of the electron beam (position relative to dopant atom, dwell time of beam, current in the beam, etc.), and therefore consists of the following:

1. Image 1 (before)
2. Beam positions in time
3. Image 2 (after)

The data is freely available here:
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6633625.svg)](https://doi.org/10.5281/zenodo.6633625)
