## Making changes to the Miro templates

If you need to make changes to the Miro template you will need to create an .rtb backup file containing the json files. An .rtb backup file is simply a standard zip file but with an .rtb extension. Using your preferred zip tool, package the json files into a zip named something like TeamTopologies.rtb. 

### PowerShell to create a Micro backup

Using Powershell Core it is now possible to run on Windows, Linux and Mac: https://github.com/PowerShell/PowerShell

```powershell
$compress = @{
  Path = "*.json"
  CompressionLevel = "Fastest"
  DestinationPath = "Team Topologies template for modelling - Miro.zip"
}
Compress-Archive @compress
# Need to rename the zip extension to rtb in order to upload to Miro
Rename-Item -Path 'Team Topologies template for modelling - Miro.zip' -NewName 'Team Topologies template for modelling - Miro.rtb'
```

Once you have created the .rtb package upload it into Miro and make any required changes. This is done using the _Upload from backup_ option:

![Screenshot of Restoring a Miro backup](Restoring%20a%20miro%20backup.png)

## Updating the  files in the repository

After you have made any necessary changes to the shapes in Miro, choose _Download board backup_ from the export menu and place the file in this folder:

![Screenshot of Exporting a Miro backup](Exporting%20a%20miro%20backup.png)

Then, using your preferred zip tool extract the archive into this folder and commit any changes.

### PowerShell to extract contents of a Miro backup

```powershell
# Need to rename the rtb extension to zip because the cmdlet only recognises zip format
Rename-Item -Path 'Team Topologies template for modelling - Miro.rtb' -NewName 'Team Topologies template for modelling - Miro.zip'
Expand-Archive -Path 'Team Topologies template for modelling - Miro.zip' -DestinationPath . -Force
```

Commit and push your changes with Git.

```
git add .
git commit -m "Comment about changes made"
git push
```

