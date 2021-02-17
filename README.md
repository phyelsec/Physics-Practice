### Activate conda:
`conda activate`

### To create an environment:
`conda create --name myenv`\
**Note:** An environment has been create at `home/anaconda/envs/`


### To create an environment with a specific version of Python:
`conda create -n myenv python=3.6`


### To create an environment with a specific package:
`conda create -n myenv scipy`
or:
`conda create -n myenv python`
`conda install -n myenv scipy`


### To create an environment with a specific version of a package:
`conda create -n myenv scipy=0.15.0`
or:
`conda create -n myenv python`
`conda install -n myenv scipy=0.15.0`


### To create an environment with a specific version of Python and multiple packages:
`conda create -n myenv python=3.6 scipy=0.15.0 astroid babel`\
**Advice:** Install all the programs that you want in this environment at the same time. Installing 1 program at a time can lead to dependency conflicts.
