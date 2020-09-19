# tools

## Install
```bash
TOOLS=$HOME/src/tools

# Set PATH to execute scripts
echo 'export PATH="'$TOOLS':$PATH"' >> $HOME/.bashrc

# Enable services
systemctl --user enable $TOOLS/update-default-audio-devices.service
```
