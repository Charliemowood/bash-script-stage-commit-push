# Bash script

This is a simple and imperfect bash script for helping automate staging, committing and pushing to git. 

## Running on your system

1. Clone the repository and change directory to the repository provided.
```bash
git clone git@github.com:Charliemowood/bash-script-stage-commit-push.git && cd bash-script-stage-commit-push
```


2. Run the following on the file to give it root permissions, otherwise you will to be root or use sudo to run the script. 
```bash
chmod +x git.sh
```

3. For usage only on your user and so you can run the script from any directory but the script in ~/repository. 
```bash
mv git.sh ~/.bin
```

4. To evoke the script. 
```bash
git.sh
```
