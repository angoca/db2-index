In order to sync the Wiki with the main code to generate the GitHub pages, it is necessary to have the main code cloned:

    git clone https://github.com/angoca/db2-index.git

Then, add a remote branch to point to the wiki, and pull the content from this unrelated repo.

```
git remote add angoca git://github.com/angoca/db2-index.wiki.git
git pull angoca master --allow-unrelated-histories
```

And finally, integrate:

    git push
