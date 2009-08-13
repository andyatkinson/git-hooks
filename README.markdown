Git hooks and an installer script. Install hooks on a per-project basis.

Installer usage: `ruby script/hookify ~/path/to/project`. Verify the hooks were installed by checking the `.git/hooks` directory for the project.

The hookify script is from [edouard](http://github.com/edouard).

You may need to `chmod +x script/hookify`