# GitHub Steps

Describe in your own words how to establish a connection between a local repository and a remote repository on GitHub.
1. First, one must initialize a local Git repository
2. Add your file to git and commit the work
3. Create a github repo
4. Set up the remote github repo by using terminal command `git remote add origin <SSH address>`
5. Check for remote directories by using informative command `git remote`
6. Push commits up to the remote respository by using terminal command `git push -u origin main`
7. Bc `-u` sets the default, or upstream branch as main, from now we can just use the command `git push` to push changes up to github instead of `git push origin main` (which would also work)
