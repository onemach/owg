#Manage Writing Using Git

1. set up a git repo.
2. commit writing template (maybe latex-based), or just an essay.
3. `owg init [git_url]` to initilize.
4. `owg create [new_essay_name]` will clone the `[master]` branch and create a new branch called `[new_essay_name]` from `master`.
5. `owg create [new_essay_name] [some_old_essay]` will clone the `[some_old_essay]` branch and create a new branch called `[new_essay_name]` from it.
6. `owg sync [essay]` to sync

##It is based on git, so all git command can be used.
