HMM-Annotation-Tools

Tools that can be used for comparing ortholog groups as HMM profiles to the Pfam database.

**Dependencies**

**Biopython**

You should install Biopython before using HMMER and HHSuite.

```pip install biopython```

Conda

If you need to install conda for HHSuite, use the following.

```
conda config --add channels bioconda
conda config --add channels conda-forge
   
   ```



**Usage**


**HMMER**

To obtain HMMER releases directly from the site, visit hmmer.org for the latest release.

Download and install latest release: 

   ```
wget http://eddylab.org/software/hmmer/hmmer.tar.gz
tar zxf hmmer.tar.gz
cd hmmer-3.3.2
./configure --prefix /your/install/path
make
make check                 # optional: run automated tests
make install               # optional: install HMMER programs, man pages
(cd easel; make install)   # optional: install Easel tools
   ```
   
   
**HMMSearch**

Use the hmmsearch.py script to run HMMER with the input MSA against Pfam.


**HHSuite**

HHSuite can be installed using conda as follows.

```
conda install -c
conda-forge -c bioconda hhsuite
```

**HHSearch**

Use the hhsuite.py script to run HHSuite with the input MSA against Pfam.
