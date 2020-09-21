# VSCode personnal config

Sharing of my vscode extensions between every machines

## Windows
To install all dependencies, execute ```path/to/myfile/extensions-installer.bat```

## Mac
First you have to install "code" as a global alias.

- Launch VS Code.
- Open the Command Palette and type 'shell command' to find the Shell Command: Install 'code' command in PATH command.

More informations : https://vscode.readthedocs.io/en/latest/setup/mac/  
To install all dependencies, execute ```path/to/myfile/extensions-installer.sh```

**Info** : To see your extensions, use this command ```code --list-extensions | xargs -L 1 echo code --install-extension```
