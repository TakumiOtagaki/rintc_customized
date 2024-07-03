# How to compute the Credibility Limits with rintc

## installation
```sh
$ cd rintc/20000524
$ make
```

## how to use
```sh
export OMP_NUM_THREADS=4 # if you want to compute with multi-core
export inputfile="/path/to/inputfile.fasta"
export outputfile="/path/to/outputfile.txt" # for credibility limit
export theta=0.5 # 0 < theta < 1.0
rintc HeatResistanceExperiment $inputfile $outputfile $theta
```
