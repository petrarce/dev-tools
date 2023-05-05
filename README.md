# Dependences
1. Repo 
2. bitbake
# Instructions
```
repo init -u file://${PWD}
cd src
BITBAKEDIR=$(realpath <path/to/bitbake>) TEMPLATECONF=$(realpath meta-dev-tools/conf/templates/default/) oe-init-build-env
bitbake <recipe-name>
```