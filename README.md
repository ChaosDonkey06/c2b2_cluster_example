# How to cluster

Connect to the cluster.
## Steps and cooking book

1. asdasd
2. 
### Create python script **hello_world.py**

```python

```

## Load python and the packages you're using




```bash
#!/bin/bash
#$ -cwd -S /bin/bash
#$ -l mem=8G
#$ -l time=18:30:
#$ -pe smp 4
#$ -N inf_01 -j y
#$ -M jc5647@columbia.edu -m aes

module load anaconda/conda3
source activate amr_hospitals
cd /ifs/scratch/msph/ehs/jc5647/amr-hospitals/test_inference_cluster

python sim_infer_weekly.py --gamma 0.015 --dir_to_save 01
```