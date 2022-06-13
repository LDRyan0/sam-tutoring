# tutoring-test
The following repository is meant as a demo to understand the basics of working with Git and contributing to open source projects.
## For Sam

- create a ```clone``` of the repository
  - this allows you to easily mirror the contents of the repository
  - you can now work freely on this *cloned* copy and then push/merge changes when you're happy
- make your own ```branch``` called **sam**
  - making your own branch allows for you to create your own independent workspace to which we can compare back to the main branch in the eventual ```pull request```
- ensure you're on the new branch by using the ```checkout``` command
- edit ```hello.py``` on your local branch so the Python script also prints ```Sam was here```
- ```add``` your changes locally
  - this is also called the *staging phase*, you can select which exact files you want to update 
  - ```git add -A``` will add all files 
  - you can use the ```git status``` command to see what changes you currently have in the staging area
- create a ```commit``` with the following message "sam was here"
  - labelling your commits is important so other people (and your future self) can keep track of what changes were made in case something goes wrong and we need to go back!
- make a ```pull request``` and I'll ```merge``` your changes if everything checks out!
  - in a pull request you should be able to view the ```diff```, it compares one branch to another (in this case **sam** to **main**)
  - ```diff``` shows you what lines have been added, removed and updated in a concise view
  
  
When you're working on a project with *hundreds of people* and a massive code base (*hundreds of thousands of lines*) imagine how difficult getting things done would be without version control!
