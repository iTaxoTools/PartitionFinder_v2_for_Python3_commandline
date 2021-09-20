# PartitionFinder v2 - adapted for Python 3

PartitionFinder 2 for Python 3

PartitionFinder is a Python program for simultaneously choosing partitioning schemes and models of molecular evolution for phylogenetic analyses of DNA, protein, and morphological data. 
You can use PartitionFinder before running a phylogenetic analysis, in order to decide how to divide up your sequence data into separate blocks before analysis, 
and to simultaneously perform model selection on each of those blocks.

https://github.com/brettc/partitionfinder

http://www.robertlanfear.com/partitionfinder/tutorial/

See the originatl publuication:

Lanfear R, Frandsen PB, Wright AM, Senfeld T, Calcott B. (2016) PartitionFinder 2: New Methods for Selecting Partitioned Models of Evolution for Molecular and Morphological Phylogenetic Analyses. Molecular Biology and Evolution 34(3):772-773 
        

---------------------


The original Partitionfinder program is not maintained anymore, and its functionalities have been included in the program IQtree. Since the simple Partitionfinder might still be useful in some cases, but the original code only runs in Python 2, we here provide a version adapted for Python 3. This work was done in the framework of the iTaxoTools project:
http://itaxotools.org/

Vences, M., Miralles, A., Brouillet, S., Ducasse, J., Fedosov, A., Kharchev, V., Kumari, S, Patmanidis, S., Puillandre, N., Scherz, M. D., Kostadinov, I., Renner, S. S. (2021). iTaxoTools 0.1: Kickstarting a specimen-based software toolkit for taxonomists. Megataxa 6: 77-92. https://www.mapress.com/mt/article/view/megataxa.6.2.1



## Quick start

```
$ git clone https://github.com/iTaxoTools/Partitionfinder_3_version_commandline.git
$ python path/to/partitionfinder.py path/to/folder/example/nucleotide
```




# Simple command line tool:

```
$ python path\to\partitionfinder.py path\to\folder\having_cfg_and_alignment_file_in_phylip_format
```

