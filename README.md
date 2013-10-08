Simple Rsync Shell
==================

This is a simple shell script that wraps rsync, to be used as login
shell for users that one wishes to be restricted to executing only
rsync. 

Care should be taken not to multiplex multiple logical users
over one system user, otherwise they'll have access to each other's
files.
