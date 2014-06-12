### Git hooks

Git repositories have a `hooks` directory that can be modofied for a given repository. This project adds a way to install and remove hooks for a project. The project has a couple example hooks.

#### Example hooks

  * post-merge: show the last 3 commits after pulling
  * pre-commit Rails hook: check for typical bad strings that shouldn't be committed

##### Install

    `ruby script/hookify /path/to/project`

##### Remove

    `rm /path/to/project/.git/hooks/hook_to_delete`

Verify the hooks were installed by checking the `.git/hooks` directory.

The hookify script is from [edouard](http://github.com/edouard).

You may need to `chmod +x script/hookify`
