[200~KosukeMuramatsu:rtmp-server KosukeMuramatsu$ git s
interactive rebase in progress; onto 4ddc570
Last command done (1 command done):
   pick bfeb2eb Add streaming server and api server
Next command to do (1 remaining command):
   fixup 7e5b060 Remove node_modules dir
  (use "git rebase --edit-todo" to view and edit)
You are currently editing a commit while rebasing branch 'master' on '4ddc570'.
  (use "git commit --amend" to amend the current commit)
  (use "git rebase --continue" once you are satisfied with your changes)

nothing to commit, working tree clean
KosukeMuramatsu:rtmp-server KosukeMuramatsu$ cd ../
KosukeMuramatsu:streams KosukeMuramatsu$ ls
api		client		rtmp-server
KosukeMuramatsu:streams KosukeMuramatsu$ git s
interactive rebase in progress; onto 4ddc570
Last command done (1 command done):
   pick bfeb2eb Add streaming server and api server
Next command to do (1 remaining command):
   fixup 7e5b060 Remove node_modules dir
  (use "git rebase --edit-todo" to view and edit)
You are currently editing a commit while rebasing branch 'master' on '4ddc570'.
  (use "git commit --amend" to amend the current commit)
  (use "git rebase --continue" once you are satisfied with your changes)

nothing to commit, working tree clean
KosukeMuramatsu:streams KosukeMuramatsu$ git rebase --continue
Successfully rebased and updated refs/heads/master.
KosukeMuramatsu:streams KosukeMuramatsu$ girt s
-bash: girt: command not found
KosukeMuramatsu:streams KosukeMuramatsu$ git s
On branch master
nothing to commit, working tree clean
KosukeMuramatsu:streams KosukeMuramatsu$ git log --online
fatal: unrecognized argument: --online
KosukeMuramatsu:streams KosukeMuramatsu$ git log --online n 5
fatal: ambiguous argument 'n': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'
KosukeMuramatsu:streams KosukeMuramatsu$ git log --oneline -n 5
971c495 (HEAD -> master) Remove node_modules dir
bfeb2eb Add streaming server and api server
4ddc570 Remove yarn.lock file
15d9fb4 Initial commit and login/logout function
KosukeMuramatsu:streams KosukeMuramatsu$ ls
api		client		rtmp-server
KosukeMuramatsu:streams KosukeMuramatsu$ cd rtmp-server/
KosukeMuramatsu:rtmp-server KosukeMuramatsu$ ls
index.js		package-lock.json	package.json
KosukeMuramatsu:rtmp-server KosukeMuramatsu$ ls -a
.			.gitignore		package-lock.json
..			index.js		package.json
KosukeMuramatsu:rtmp-server KosukeMuramatsu$ npm i
npm WARN rtmp-server@1.0.0 No description
npm WARN rtmp-server@1.0.0 No repository field.

added 63 packages from 49 contributors and audited 136 packages in 1.994s
found 0 vulnerabilities

KosukeMuramatsu:rtmp-server KosukeMuramatsu$ git s
On branch master
nothing to commit, working tree clean
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## What is this?

### This app would be like twitch for street dance :)
