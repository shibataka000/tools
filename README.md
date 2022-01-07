# tools

## Install
```bash
TOOLS=${HOME}/src/tools

# Set PATH to execute scripts
echo 'export PATH="'${TOOLS}':$PATH"' >> ${HOME}/.bashrc

# Add `docker rma` plugin
mkdir -p ${HOME}/.docker/cli-plugins
ln -s ${TOOLS}/docker-rma ${HOME}/.docker/cli-plugins/
```
