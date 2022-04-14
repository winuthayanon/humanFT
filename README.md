# humanFT

# How to create new conda environment
conda env create -n winuthayanon-lab -f winuthayanon-lab.yml
conda activate winuthayanon-lab

# How to add kernel
python -m ipykernel install --user --name winuthayanon-lab --display-name "winuthayanon-lab"

# How to remove kernel
jupyter kernelspec list
jupyter kernelspec remove -f winuthayanon-lab

# How to remove conda environment
conda env list
conda remove --name winuthayanon-lab --all

# How to export conda environment
conda-env export -n winuthayanon-lab -f winuthayanon-lab.yml 
