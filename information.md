# Default fish history path
/home/$USER/.local/share/fish/fish_history



# Vertical Workstation Setup
`sudo apt install gnome-shell-extension-manager` Search for extensions: V-Shell (Vertical Workspaces)


# Install Dropbox Headless via command line:
The Dropbox daemon is only compatible with 64-bit Linux servers. To install, run the following command in your Linux terminal.
`cd ~ && wget -O - "https://www.dropbox.com/download?plat=lnx.x86_64" | tar xzf -`
Next, `run the Dropbox` daemon from the newly created .dropbox-dist folder.
`~/.dropbox-dist/dropboxd`


# Install yq
curl -fsSL -o yqq https://github.com/mikefarah/yq/releases/download/3.3.0/yq_linux_amd64
chmod +x yqq
sudo mv yqq /usr/local/bin/yqq
pip3 install yq               -->   pip3 install yq --break-system-packages
                                  +
nano ~/.bashrc
export PATH="/home/appscodepc/.local/bin:$PATH"