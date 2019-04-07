DevSync script for remote dev server development. Created for projects that rely on Stingle PHP framework.

Setup:

1. Place devsync script in ~/bin/ or /usr/local/bin directory
2. Make it executable: chmod +x /path/tp/script/devsync
3. Create folder in your user's home directory named: devsync
4. Place sample config file in that directory (default config file name should be: default)
5. Edit config file according to your needs
6. Enjoy devsyncing :)

Help:

	devsync [opts] PROJECT_NAME [PROJECT_NAME] ...

	-h, --help
		show this help text
	-d, --delete-cache
		Selete Stingle cache after sync
	-r, --reverse
		Do a reverse sync. Sync dev server to local copy
	-f, --fix-perms
		Fix project permissions
	-n, --no-sync
		Do not make sync, just do other stuff
	-u, --user
		Override user
	-z, --host
		Override host
	-l, --local-dir
		Override local dir path
	-w, --remote-dir
		Override remote dir path
	-p, --params
		Override rsync params
	-c, --config
		Config file name. Default: default
	-q, --config-dir
		Config file dir. Default: ~/devsync/