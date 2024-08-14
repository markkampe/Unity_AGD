The Unity Associate Game Developer course involves a series of units,
introducing the editor and the managerment of different aspects of
scenes and objects.  This is a simple template with:
 - a (empty) sub-directory for each unit's project
 - .gitignore to exclude standard and built (vs created) items

The intent is that students will fork this repo and then do the work
in their own fork.  The expected form of a submission is a github
URL for the (public) repo in which you have done your work.

If you create each project (under the top level directory, with the
same name as the corrisponding unit sub-directory), all files for that
project will be put in that sub-directory.

If you then do a "git status" to see what has been added (but not
ignored) and a "git add" for those files/sub-directories, your
work (but not the libraries on which you depend and created work-products)
can be pushed back to your repo.

If you want to recreate a project from such a git repo:
   - clone your repo
   - in UnityHub, add a new project from disk
     giving it the name of the desired unit sub-directory
   - the unity editor will automatically re-import all of 
     the libraries on which you depend
   - once that is complete, you should be able to Play from
     the new clone.

The above process is roughly equivalent to simply copying the
Assets, Packages, ProjectSettings and UserSettings sub-directories.

If you are not concerned about git version control, a simpler way to
export a project from one system to another is:
   1. in Project window, right-click the Assets folder and select Export Package
   2. in the resulting dialog, review the list and click Export
   3. give the package an identifying name (e.g student name and project #)

Such an export should be platform independent, so that a project developed
on a Windows system can be imported into and run on a Linux system.
