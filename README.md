# …or create a new repository on the command line
# echo "# learning-java" >> README.md
# learning-java
# git init
# git add README.md
# git commit -m "first commit"
# git branch -M main
# git remote add origin https://github.com/hello0zai/learning-java.git
# git push -u origin main

# …or push an existing repository from the command line
# git remote add origin https://github.com/hello0zai/learning-java.git
# git branch -M main
# git push -u origin main

hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint:
hint:   git config --global init.defaultBranch <name>
hint:
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint:
hint:   git branch -m <name>
Initialized empty Git repository in /e/learning-java/.git/


git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/hello0zai/learning-java.git'


git push -u origin
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

git config --global user.email "you@example.com"
git config --global user.name "Your Name"


git commit -m "init"
[main (root-commit) 97d9249] init
 1 file changed, 26 insertions(+)
 create mode 100644 README.md

git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


git push --set-upstream origin main

git push --set-upstream origin main
Username for 'https://github.com':
Password for 'https://hello0zai@github.com':
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/hello0zai/learning-java.git/'



remote: Support for password authentication was removed on August 13, 2021.
https://stackoverflow.com/questions/68775869/message-support-for-password-authentication-was-removed
