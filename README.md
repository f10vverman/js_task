Project installation
To install dependencies run:

npm install

Basic commands
npm run test - to execute unit tests

How to update your fork from upstream
First in your forked repo add this repositiry as an upstream (upstream is just an alias):

git remote add upstream https://github.com/griddynamics/ui-internship-lwo2

Then on your master branch run:

git fetch upstream (get all updates from the upstream)

git rebase upstream/master

git push

Then you master branch will be up-to-date with upstream

To update specific branch:

Checkout your branch

git fetch upstream

git rebase upstream/master or git merge upstream/master

git push
