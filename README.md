# star_fusion
Snakefile that runs STAR-Fusion. 

# Usage
First, create an isolated conda environment as following. 
```
conda create -n star -c bioconda star star-fusion
```

# Run
```
snakemake -p -k -s star_fusion.sm -j 24
```

