# tools

## Install
```bash
TOOLS=$HOME/src/tools

# Set PATH to execute scripts
echo 'export PATH="'$TOOLS':$PATH"' >> $HOME/.bashrc

# Add symlink to run services by systemd
ln -sf $TOOLS/update-default-audio-devices.service $HOME/.config/systemd/user/
systemctl --user enable update-default-audio-devices
```
