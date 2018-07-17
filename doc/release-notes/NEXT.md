* When cloning a whole TFS Project Collection (``$/``) without specifying a local repository name, clone into "tfs-collection" instead of erroring with "Invalid Path". (#1202)
* Init --autocrlf now defaults to the global core.autocrlf settings instead of false and line endings are now properly normalized when pushing changes to TFS (#1210 by @JeffCyr)
