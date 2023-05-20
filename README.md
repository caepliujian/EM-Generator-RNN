# **EM-Generator-RNN Users Guidance** #
RNN based molecular generation module (suitable for fused-ring nitro compounds). 

## Author: ##
- **Dr. Jian Liu**, liujian-12@caep.cn, Institute of Chemical Materials, CAEP
## Requirements:  ##
1. ananconda
2. python 3.8
2. scikit-learn 1.1.1
4. rdkit 2022.9.5
5. torch 1.12.0
6. pandas 1.4.3
7. numpy 1.24.3
## Usage: ##

    python EM_Generator_RNN.py [-h] [-i MODELDIR] [-n NUMBER] [-a] [-s] [-r]


*      optional arguments:
    
      -h, --helpshow this help message and exit
    
      -i MODELDIR, --modelDir (model dir name)
    
      -n NUMBER, --number (number of molecules to generate)
    
      -a, --allMolecules (keep non-energetic molecules)
    
      -s, --smilesOnly(build smiles only, do not create *.mol files)
    
      -r, --keepRedundancy (keep redundant molecules)*
## Example: ##
    python EM_Generator_RNN.py -i FusedRing

*The results will be written to **Result**.*