# sphinx2github

BASH script to automate Sphinx-doc publishing and hosting on Github pages

* Save this script your current current Sphinx-doc project source directory

* Script presumes you want to build latexpdf and html targets only (you can customize this more)

This script assumes you have initialized your directory and set it as origin for your remote repo (check it):

git remote add origin your-repo-address
git remote -v

**What this script does**

* Build sphinx-doc target outputs (latexpdf, html) to default _build/ directory

* Move the directory _build/html/ to docs/

* Add a .nojekyll flag-file to disable GitHub Page's default Jekyll stylesheet

* Add new content, commit and push to your master repo, including sub-directory docs/ that hosts your html files

**Warning**

  If you do hosting from a Private Repo, then make sure you set up your SSH Keys.
  Store it in your local machine and also on your Github repo site. Follow these directions here: https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/





  
