## File sturcture

<!-- link to images -->
![File structure](/images/file-structure-root.png)
This from this file structure, we can see seveal folders 

4 drwxr-xr-x 1 AzureAD+AlexisTroïtzky 4096    0 Nov 10 15:36 ./
 4 drwxr-xr-x 1 AzureAD+AlexisTroïtzky 4096    0 Nov 11 09:36 ../
 4 drwxr-xr-x 1 AzureAD+AlexisTroïtzky 4096    0 Nov 11 09:50 .git/
 0 drwxr-xr-x 1 AzureAD+AlexisTroïtzky 4096    0 Jul 12 10:07 .github/
 1 -rw-r--r-- 1 AzureAD+AlexisTroïtzky 4096   27 Nov 10 15:36 .gitignore
 0 drwxr-xr-x 1 AzureAD+AlexisTroïtzky 4096    0 Aug 16 14:26 .vscode/
 0 drwxr-xr-x 1 AzureAD+AlexisTroïtzky 4096    0 Jul 12 10:07 database/
 4 drwxr-xr-x 1 AzureAD+AlexisTroïtzky 4096    0 Nov 10 10:25 docker/
 4 -rw-r--r-- 1 AzureAD+AlexisTroïtzky 4096  828 Oct 30 14:38 docker-compose.yml
 4 -rw-r--r-- 1 AzureAD+AlexisTroïtzky 4096 2827 Nov 10 15:36 Dockerfile
 4 -rw-r--r-- 1 AzureAD+AlexisTroïtzky 4096  760 Jul 12 10:07 Makefile
 8 -rw-r--r-- 1 AzureAD+AlexisTroïtzky 4096 4381 Jul 12 10:07 README.md
 0 drwxr-xr-x 1 AzureAD+AlexisTroïtzky 4096    0 Jul 12 10:07 scripts/
28 drwxr-xr-x 1 AzureAD+AlexisTroïtzky 4096    0 Nov 11 10:28 src/

the .git folder contains git files and is hidden

the .github folder contains the continuous-deployment.yaml file.

the .gitingore file contains the files that are ignored by git.

the .vscode folder contains the settings.json file and the launch.json file. Settings is the user settings, in mine it's just colors for the vscode peacock extension. The launch.json file is for debugging using xdebug, it contains the configuration for the debugger.

the database folder contains a very long sql file that seems to create the database for suitecrm as well as some default data.

the docker folder contains files related to the docker configuration

the scripts folder contains one file, scripts\export-to-big-query.sh, which is a bash script that exports the database to big query.

the src folder contains the source code for suitecrm. It contains a lot of folders and files.

the 