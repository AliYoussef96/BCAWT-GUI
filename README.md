# BCAWT-GUI

# Statement of Need

BCAW Tool manages a complete automated workflow to analyze the codon usage bias for genes and genomes of any organism. For thus who can not use python, we provide here a GUI software that can work on any operating system, with the minimal requirement.

# Installation Instructions

1. Install  Python >=3.7.
2. Download BCAWT using this command

```python
pip install BCAWT
```
3. Download this [zip file](https://github.com/AliYoussef96/BCAWT-GUI/tree/master/BCAWT-GUI). After, compress the file and run BCAWT-GUI.py script by any way you would like. 

# Usage

1- Run the "BCAWT-GUI.py"

![](https://raw.githubusercontent.com/AliYoussef96/BCAWT-GUI/master/steps/1.png)


2. Import a fasta file contains the genes you want to test (from "Open fasta file" button).

![](https://raw.githubusercontent.com/AliYoussef96/BCAWT-GUI/master/steps/2.png)

2. Enter the genetic code your genes use (for more information see: [NCBI](https://www.ncbi.nlm.nih.gov/Taxonomy/Utils/wprintgc.cgi)) 
3. Choose a directory (folder) you want to save the result in (from "Save in" button). 

![](https://raw.githubusercontent.com/AliYoussef96/BCAWT-GUI/master/steps/3.png)

4. Import a fasta file contains genes that will be used as a reference set (or just do not use it if you want BCAWT to generate the reference set automatic, for more information see: [BCAWT](https://bcaw-tools-documentation.readthedocs.io/en/latest/Intro.html)) (from "Open Reference" button). 
5. Now, just Run it. Wait for the loading bar to finish.

![](https://raw.githubusercontent.com/AliYoussef96/BCAWT-GUI/master/steps/4.png)


# Contribution Guidelines
**Contributions to the software are welcome**

For bugs and suggestions, the most effective way is by raising an issue on the github issue tracker. 
Github allows you to classify your issues so that we know if it is a bug report, feature request or feedback to the authors.


## Citation

Anwar, (2019). BCAWT: Automated tool for codon usage bias analysis for molecular evolution. Journal of Open Source Software, 4(42), 1500, https://doi.org/10.21105/joss.01500
