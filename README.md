# HMM-Annotation-Tools
Tools that can be used for comparing ortholog groups as HMM profiles to Pfam.


You should install Biopython for optimal use. 



HMMER 

To obtain HMMER releases, visit hmmer.org for the latest release.

Download and install latest release: 

   % wget http://eddylab.org/software/hmmer/hmmer.tar.gz
   % tar zxf hmmer.tar.gz
   % cd hmmer-3.3.2
   % ./configure --prefix /your/install/path
   % make
   % make check                 # optional: run automated tests
   % make install               # optional: install HMMER programs, man pages
   % (cd easel; make install)   # optional: install Easel tools



HHSuite

HHSuite can be installed using conda as follows.

# install via conda
conda install -c conda-forge -c bioconda hhsuite 


