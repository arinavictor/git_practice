#Distributed Version Control System:
    There is no single "central" version of the code base, instead every person has a working copy and a full history of all changes. Allows branching and merging and speeds up most operations. 
    - central and branch repositories 
    - pull requests (aka merge request)

    *can give you off network access
    *more security concerns
        -everyone has a copy
    *allows multiple people to work at the same time
    *more collaboration

##GIT FLOW
    - Stage, Commit, Push 

    * I DO (add new file)
        - git status... returns untracked file
        - git add file_name ... watches the file for changes (stages it)
            *git add . stages everything
            *anytime you make changes you have to stage it again
        - commit = save 
            *git commit -m "Adds notes."
                - short message to describe the commit
                 "-m" = message flag
        - git push origin master 
            *master = branch 
            *origin = repo x


        ** git remote -v  tells you the remote repositories you are pulling from          