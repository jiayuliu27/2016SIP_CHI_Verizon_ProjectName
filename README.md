# 2016SIP_CHI_Verizon_ProjectName
Sample project 
- main things to note:
 - code organization
 - how github works commits, merge requests, conflicts
- General guidelines 
    - before you pull code from your repo, make sure that you are on the right branch on command line
        - `git branch` or `git status` will tell you which branch you are on
    - switch branch if needed
        - `git checkout master` // this will switch your folder to your master branch
                            // this branch should be the one you want to make a copy of to
                            // work on the new feature
    - then check out a new branch and give it a descriptive name of what feature you want to work on
        - `git checkout -b fix_homepage_button_link`
                            // this creates a new branch named fix_homepage_button_link
                            // and is a copy of the branch you checked out in prev step
    - then you can go into your project folder and make changes in your files, add or delete file
    - after you're done making a change, commit the changes with a descriptive message
        - `git add myfile.html` // adds myfile.html to the staging area to be committed
        - `git commit -m "change button links"` // commits the myfile.html changes with the message
    - then push your code to your repository
        - `git push origin fix_homepage_button_link` 
                            // if an error occurs here, head over to the Extraresources(1).pdf
                            // on canvas, you will find a link to google slides with solution
    - at this point, your work on this branch is done
    head over to your account on github and create a merge requests with base master
    it will show you if there are any conflicts, resolve them first, and then submit the request
    and one of your teammates should review this branch for you (meaning test it to make sure no bugs)
    if all goes well, your code will get merged to master branch and be part of the final product!
