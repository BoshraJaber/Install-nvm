# Install-nvm
Installing nvm requirements to run node using zshell

* Open `.zshrc` file and add the following code: (This can be done from the root folder -> `code .` -> from vs code edit the `.zshrc` file or form the command line `nano .zshrc`)
```
export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
 [ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm
```
* `sudo apt install curl `
* `curl https://raw.githubusercontent.com/creationix/nvm/master/install.sh | bash `
* `nvm install node ` or `nvm install 12.18.3`
* To check node version: `node --version`

## Updat npm:
`sudo npm install -g npm@latest`
