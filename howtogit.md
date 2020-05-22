Howto
=====

Undo last commit
----------------

Rewind HEAD and preserve changes:

    git reset --soft HEAD~1
    
Rewind HEAD and drop changes:

    git reset --hard HEAD~1
    
Forse-push to the remote `origin`:

    git push origin -f


