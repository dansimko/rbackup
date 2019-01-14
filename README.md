# rbackup

rbackup is a simple script utilizing rsync and ssh to securely backup data.

## usage

	$ rbackup

and that's it.

## configuration

The default path to the script configuration is `$HOME/.config/rbackup/config`, which can be overriden by specifying your configuration file as the first argument passed on the command line. A sample (empty) configuration file is called `rbackup.conf`.
