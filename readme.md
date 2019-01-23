Please read the following instruction in order to make your exam experience as smooth as possible:

dotnet: 

-make sure you have installed on your machines at least dotnet 2.1 (although we did tell in the lesson to have 2.0 installed, but 2.1 provides backward support for the project). 

The link for the installation is: 

-https://www.microsoft.com/net/download?initial-os=windows. 

The link for removing dotnet is: 

-https://docs.microsoft.com/en-us/dotnet/core/versions/remove-runtime-sdk-versions?tabs=Windows 

Typescript/react: 

-make sure you have node installed in your computers with NPM or YARN. For windows users you can download YARN via CHOCO (https://chocolatey.org). download the attachment which includes an empty react project similar to the one of the exam. You can test your installation with it prior tomorrow.  

At the beginning: 

-run the command "dotnet restore" and "npm install" or "yarn"  to download all the packages needed for the project

Recommendation: 

-deal with one part at a time, so for example the model first then the controller, and in the end the view; this should help you with testing progressively your applicaiton

Useful comands: 

-"dotnet build", 
-"dotnet run", 
-"dotnet ef migrations add <name>", 
-"dotnet ef database update", 
-"dotnet ef databse drop", 
-".\node_modules\.bin\webpack -w (windows users) or "./node_modules/.bin/webpack -w (macos users)
