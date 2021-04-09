In order to sync the Wiki with the main code to generate the GitHub pages, it is necessary to have the main code cloned:

    git clone https://github.com/angoca/db2-index.git
    cd db2-index

Then, add a remote branch to point to the wiki, and pull the content from this unrelated repo.

```
git remote add angoca git://github.com/angoca/db2-index.wiki.git
git branch -a
git pull angoca master --allow-unrelated-histories
```

And finally, integrate:

    git push

For following execution, it is just necessary to do:

    git pull angoca master
    git push
