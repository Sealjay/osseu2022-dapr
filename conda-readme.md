## Create the environment
1. Update conda: `conda update conda`
2. Create the environment (Call it ossdapr) `conda create -n ossdapr python=3.10`
3. Activate the environment: `source activate ossdapr`
4. Install all required packages: `conda install --file ossdapr.req`.
5. Get some space back: `conda clean -a`
6. Start the notebook server: `jupyter notebook`