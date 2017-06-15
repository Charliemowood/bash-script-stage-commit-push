# Bash script

This is a simple and imperfect bash script for helping automate staging, committing and pushing to git. 

## Running on your system

1. Clone the repository and change directory to the repository provided.
```bash
git clone git@github.com:Charliemowood/bash-script-stage-commit-push.git && cd bash-script-stage-commit-push
```


2. Run the following command on the file to give it root permissions, if you do not do this you will need to be root or use sudo to run the script. 
```bash
chmod +x git.sh
```

3. For usage for your user only: run the command below to put the script in the ~/.bin repository. This allows you to run the script in any repository without having to refer to the scripts location.
```bash
mv git.sh ~/.bin
```

4. To evoke the script. 
```bash
git.sh
```
