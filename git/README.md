# Git Basics

Here I will list down basic commands and steps for getting started and using git.

1. First thing is install git in your machine (Installation differs on each OS platform)
2. Open an account on [github](https://github.com) or [gitlab](https://gitlab.com) or any other service
3. Create a folder/directory on your local machine (ex: knol) and Open a terminal/command window and cd to that folder.

   ```
   $ cd knol
   ```
   ```
   $ git init
   ```

4. Then create a README.md file and open it with gedit (Note: md extension means its a markup file, read more about [markdown](https://guides.github.com/features/mastering-markdown/))

   ```
   $ touch README.md
   ```
   ```
   $ gedit README.md
   ```

5. Write something in the read me file (use markup to format the content) and save it.
6. Then do 

   ```
   $ git status
   ```
   ```
   $ git add *
   ```
   ```
   $ git commit -m 'First Commit'
   ```

7. create a repository on git with the same name as the folder you created above (knol)
8. Then

   ```
   $ git push -u origin master
   ``` 

9. Enter your github/gitlab credentials and press enter, this will push your README.md file into your knol repository. You can also setup ssh so that you don't have to enter your credentials everytime you want to push your changes to github/gitlab.



Note: GUI Clients: Alternatively one can use GUI clients like [GitExtensions](http://gitextensions.github.io/), [Github Desktop](https://desktop.github.com/)
