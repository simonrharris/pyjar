# pyjar
A python implementation of the joint ancestral state reconstruction algorithm of Pupko et al

## Contents
* [Requirements](#requirements)
* [Usage](#usage)
* [Citation](#license)
* [License](#license)

## Requirements
pyjar requires python3 and the following modules: Bio, dendropy, numpy, scipy.

## Usage
```
usage: usage: pyjar.py [options]

  -h, --help            show this help message and exit
  -a FILE, --alignment FILE
                        Input alignment file. Required.
  -i FILE, --info FILE  Input RAxML info file. Optional. By default a JC model
                        will be applied.
  -t FILE, --tree FILE  Input tree file. Required.
  -o PREFIX, --output_prefix PREFIX
                        Output prefix. Required.
  -v, --verbose         More verbose output
```

## Citation
For the joint ancestral reconstruction method, please cite "Tal Pupko, Itsik Pe, Ron Shamir, Dan Graur; A
Fast Algorithm for Joint Reconstruction of Ancestral Amino Acid Sequences,
Molecular Biology and Evolution, Volume 17, Issue 6, 1 June 2000, Pages
890-896

## License
pyjar is free software, licensed under [GPLv3](https://github.com/simonrharris/pyjar/blob/master/LICENSE).
