## Singularity container build script for riboSeqR and baySeq

Both packages are obtained from Bioconductor and require RCurl as a prerequisite.

RCurl needs the Ubuntu `libcurl-dev` package which is also installed

To build:

`sudo singularity build riboseqbayseq.simg Singularity`


