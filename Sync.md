In order to sync the Wiki with the main code to generate the GitHub pages, it is necessary to have the main code cloned:

    git clone https://github.com/angoca/db2-index.git
    cd db2-index

Then, add a remote branch to point to the wiki.

```
git remote add angoca git://github.com/angoca/db2-index.wiki.git
git branch -a
```

And finally, pull changes and integrate them into the other:

    git pull angoca master --allow-unrelated-histories
    git push
