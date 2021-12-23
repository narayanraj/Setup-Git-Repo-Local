# Setup-Git-Repo-Local
How to setup Git Repo from Azure devOps on Local system <p>

<b>1. Consider a Project in Azure Devops account - "MyProject"</b></br>
This need to be stored Locally to perform further/Fresh development from Local windows system.</br>

<b>2. Select "Clone" option from Azure devops Project account</b></br>
Goto : MyProject/anyFolder --> Repo --> Files --> Clone</br>

<b>3. Click Clone-in-VS-Code option OR select your IDE</b></br>
This will lead your IDE to select Location where the MyProject source folder to be created.</br>

<b>4. Select a Destinatoion folder for Git Source files download</b></br>
 At this location on local system the Git Repo will be created with same name.</br>

<b>5. Files from selected Repo/Folder now Cloned to Local folder</b></br>
The folder with project/repo name will de created here with files included.

<b>6. Open this folder with "Open-with-Code" option</b></br>
 This will open the MyProject folder with Vscode IDE. Do the code changes and save.</br>
  
<b>7. Commit the changes & Push to Azure devops Repo </b></br>
Sometimes, Git needs user.name & user.email for the push to succeed initially.</br>
Use the commands in terminal to create git config for this project only :</br>
<b>--> git config user.name "firstname lastname" </br>
--> git config user.email "emailid@mail.com"</b></p>

Happy coding !!
