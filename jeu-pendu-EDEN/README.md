# Jeu du pendu <!-- omit in toc -->
il faut ajouter un dossier dans le dossier general qui doit se nommer .vscode
dans le fichier il dois y avoir un document text qui se nomme 
launch.json a l'interieure du fichier launch il doit y avoir :
{
    // Use IntelliSense to learn about possible attributes.
    // Hover to view descriptions of existing attributes.
    // For more information, visit: https://go.microsoft.com/fwlink/?linkid=830387
    "version": "0.2.0",
    "configurations": [
        {
            "type": "chrome",
            "request": "attach",
            "name": "Attach to Chrome",
            "port": 9222,
            "webRoot": "${workspaceFolder}"
        }
    ]
}



[penduu.txt](https://github.com/BLAZDA93/Eden-pendu/files/6570325/penduu.txt)
