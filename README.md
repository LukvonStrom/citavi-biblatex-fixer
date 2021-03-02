# citavi-biblatex-fixer
This repo contains js code to fix the biblatex output of Citavi for the DHBW citation style (removes isbn, doi, abstract, ...)

## Configure Biblatex export in Citavi
### Prerequesites  
You need to have node.js installed  
You need to execute `npm install` in this directory  
You need to follow the instructions below to configure a file export in Citavi.
### Enable LaTeX Support
![alt text](./optionen.png "Logo Title Text 1")
![alt text](./latex-settings.png "Logo Title Text 1")

## Create Export Profile
![alt text](./new-profile.png "Logo Title Text 1")
![alt text](./export.png "Logo Title Text 1")
![alt text](./export-all.png "Logo Title Text 1")
![alt text](./citavi-export-file.png "Logo Title Text 1")
=> Replace the file in this folder

![alt text](./biblatex-export.png "Logo Title Text 1")

![alt text](./set-profile.png "Logo Title Text 1")
=> voila, you can now call this export at any time and it exports right in this directory.

### Execute the script
Now use `node index.js` to get the correct biblatex output in your clipboard