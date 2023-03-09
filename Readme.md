### This is a simple guide -pushing your first code to github

 #### In Windows
    Make a folder
     ```sh
       Gitty
     ```
    inside the folder make a file 
     ```sh
        index.html
       ```
    initialize git by this command
    ```sh
     git init
    ```                           
    add the untracked code by this command
    ```sh
     git add index.html
     ```
     or add all
     ```sh
    git add .
    ```
    Commit all changes by this command
     ```sh
     git commit -m "<your message>"
     ```
#### Before pushing to your remote
    1.Navigate to your github repos and create a new repository name it Gitty
    <img src="https://github.com/Francis-Mwaniki/Gitty/blob/main/img/gity.png"/>
    2.Select the second option (Existing code from your local Pc)
    3.Copy the command
    ```sh
    git remote add origin git@github.com:<replace your github username>/Gitty.git
    git branch -M main
    git push -u origin main
    ```
#### that's it Happy coding
