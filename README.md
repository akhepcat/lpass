# lpass

Bog stupid 'keypass' clone via git and gpg
lpass - local password manager

Install:
1) create a new git repository
2) copy lpass into the new git repository and commit it
3) initialize the database:
  3a) touch accounts.txt
  3b) gpg -o accounts.txt.gpg -c accounts.txt
  3c) rm accounts.txt
4) commit the gpg-encrypted database file
5) test lpass editing, and allow your changes to commit.
6) revel

usage:

    $ lpass (options) {search-string}
    	-c, --clear-authcache	 Clears the gpg auth-cache
    	-f, --force-sync 	 Force an update with the remote
    	-e, --edit		 Edit the local auth store
    	-h, --help		 this help.


Don't even bother using it.  It's just dumb.  

It's simply a "prove you can do it" kind of exercise.

Yes, it runs on your Android phone under Termux.  Don't do it. Really.
