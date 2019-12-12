This file contains the notes I was taking when I created this application.

I needed to have dotnet installed to be able to create this project. This can
be done by doing the following commands in your terminal:
    wget -q https://packages.microsoft.com/config/ubuntu/18.04/packages-microsoft-prod.deb  
    sudo dpkg -i packages-microsoft-prod.deb  
    sudo add-apt-repository universe  
    sudo apt-get install apt-transport-https  
    sudo apt-get update  
    sudo apt-get install dotnet-sdk-2.2  
    dotnet –version  

(last command only checks for your version)
Now, the next step is to create this project. Create a new directory, and open
a terminal from this new directory. Type:
    dotnet new mvc

Then the ASP.NET template will be generated.
Once you are ready to run your project, type in this directory from the terminal:
    dotnet run

Note that I tried using MonoDevelop, but it is too complicated to use. I got weird errors and I do not want to try developping using that IDE.

I am trying to do my work with VS code, let's see how it goes...
