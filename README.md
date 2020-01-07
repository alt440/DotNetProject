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

Note: You can also type
    dotnet new
and a list of choices of projects will be displayed.

Then the ASP.NET template will be generated.
Once you are ready to run your project, type in this directory from the terminal:
    dotnet run

Note that I tried using MonoDevelop, but it is too complicated to use. I got weird errors and I do not want to try developping using that IDE.

I am trying to do my work with VS code, let's see how it goes...

Update:
I have decided to not continue this project as ASP.NET has been fully customized to use objects that are uncommon. I have looked into NET CORE 3 Projects and I have been surprised at how little I am able to completely understand. I do not believe NET CORE will help further my career, so I have dropped it for now.

Here are the resources I have used so far:
 - https://www.youtube.com/watch?v=bIiEv__QNxw
 - https://www.youtube.com/watch?v=phyV-OQNeRM
 - C# 8 and .NET Core 3 Projects Using Azure - Second Edition
