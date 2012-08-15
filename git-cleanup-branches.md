# Clean up branches in a repo

1) List merged branches

    git branch --merged

2) For each branch, delete oldones

    git branch -d oldbranch && git push --delete origin oldbranch

3) Review unmerged branches

    git branch --nocd ~/Sites/browserid-vagrant-scilinux/-merged