## incomplete-interactome

This folder contains files which are used to convert the disease names used in the interactome created by
*Menche et al.* in their paper ["Uncovering disease-disease relationships through the incomplete interactome"](dx.doi.org/10.1126/science.1257601) to their
MeSH ID's.

SciencetoMESHterm.ipynb file is an ipython notebook file. It takes the disease_input.txt file, and queries MeSH (2014)
to obtain the relevant MeSH ID's that match the disease names. It returns the disease_output.tsv file which is a list
of the diseases and their respective ID's. 

