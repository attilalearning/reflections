#When would you want to use a remote repository rather than keeping all your work local?#

    If I want to collaborate with others I would use a remote repository
    like GitHub. But also, if I would like to make my project available to
    others or to get feedback from others, I would use a remote repository
    too.

#Why might you want to always pull changes manually rather than having Git automatically stay up-to-date with your remote repository?#

    Probably because I could have some uncommitted changes in my working
    directory and so, if an auto-update would be performed, I assume I
    would loose my changes?!

#Describe the differences between forks, clones, and branches. When would you use one instead of another?#

    Branches are used when we want to experiment within our project.

    We do clones when we want to "download" a project that is on GitHub or
    when we want to create a copy of one of our projects locally, to a
    different location on our own computer.

    And we use fork to copy someone else's project on GitHub (to our own
    account, still on GitHub). By using fork, we let the original creator of
    the project know about us having a copy (and also, as I've seen the
    options on GitHub, we may, later on, push the changes we made to such a
    project to the original repo on GitHub).

#What is the benefit of having a copy of the last known state of the remote stored locally?#

    When we have the last known state od the remote stored locally, we can
    check to see the changes and the branches (graph). Then, we can decide
    if any merging is needed and can proceed if so.

#How would you collaborate without using Git or GitHub? What would be easier, and what would be harder?#

    Should there be no GitHub, we would invent one! :D

    Well, without GitHub, we could perhaps use zip files & ftp servers?
    This would take more time since we would need to pack, upload, then
    someone else would need to download, unpack, check for changes, do
    the merging etc. All mergings into the master or main stream would
    need to be done by the code's owner? I can't think of anything that
    would be easier by not having GitHub.

#When would you want to make changes in a separate branch rather than directly in master? What benefits does each approach have?#

    When merging a new feature in a collaborative project and where more
    changes have been made at the same time, it's wise to try and merge
    the change into a separate branch fiirst, sorting out all the conflicts
    locally and presenting the "merged" node or version on GitHub so that
    the owner can decide easily if he/she would allow the merge into his/
    her master branch (since the merge has already been made, there should
    be no trouble, no conflict, only a decision is left to be made).

