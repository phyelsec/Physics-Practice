![GitHub last commit](https://img.shields.io/github/last-commit/phyelsec/Physics-Practice?logo=Github&style=plastic)

## Basic Conda management commands:

**Activate conda:**\
`conda activate`

**Modify the default packages:**\
In `create_default_packages` section of your `.condarc` configuration file, you can add those programs you want being installed everytime you create a new environment.

**To create an environment with default packages:**\
`conda create --name myenv`\
**Note:** An environment has been create at `home/anaconda/envs/`

**To create an environment without the default packages:**\
`conda create --no-default-packages -n myenv python`

**To create an environment with a specific version of Python:**\
`conda create -n myenv python=3.6`

**To create an environment with a specific package:**\
`conda create -n myenv scipy`\
or: \
`conda create -n myenv python`\
`conda install -n myenv scipy` 

**To create an environment with a specific version of a package:**\
`conda create -n myenv scipy=0.15.0`\
or: \
`conda create -n myenv python`\
`conda install -n myenv scipy=0.15.0`

**To create an environment with a specific version of Python and multiple packages:**\
`conda create -n myenv python=3.6 scipy=0.15.0 astroid babel`\
**Advice:** Install all the programs that you want in this environment at the same time. Installing 1 program at a time can lead to dependency conflicts.
