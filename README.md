======
Macros
======

1. `git-change-url`: 
    - Description: allows to switch between https and ssh the remote in a git repo
    - Usage: 
        - `git-change-url` --to-ssh convert https url to ssh
        - `git-change-url` --to-https conver ssh url to https one.

2. `py_switch`: allows to switch between py 3.5 and py 2.7, working only on
    MacOS using macport

3. `set_all_remote`: change all remote from one username to another. Actually
   setup to change Baaaaam into bam241... Can be easily change if needed...

4. `c_git`: 
    -Usage: 
        - without `args`, check if the actual folder is under git versionning, if
          not `git init` it, then create a new ``GitHub`` named as the root folder
          and add the remote,
        - with `args, create a new ``GitHub`` repo name as the `args`, then
          clone it locally.
