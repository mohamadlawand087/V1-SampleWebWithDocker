Environment Setup:

•	Download docker: https://www.docker.com/products/docker-desktop
•	Download dotnet core SDK: https://dotnet.microsoft.com/download
•	Download Visual Studio Code: https://code.visualstudio.com/download

Extra:
Visual studio code extension:
-	C #
-	Docker

Coding:
-	Open terminal for mac 
-- Command + space bar 
-- Type terminal 
-	Open PowerShell on windows
-- Go start menu
-- Type power shell
-	Navigate to the dev folder
-	Create a dotnet application
-- dotnet new mvc -n “SampleWebWithDocker” -lang “C#” -au none 
-	Open VS Code in that folder 
-- code . 
-	Run the application locally to make sure everything is as it should be
-- dotnet build
-- dotnet run
-	Add docker file
-- In the root directory of the project 
-- Add a new file called Dockerfile
