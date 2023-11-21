


Delete all git history. This can be useful if you wish to keep all files but remove all commits attached to it, for reasons such as password safety.
Note that this is like resetting everything and history of all files will be lost.

1. Start with opening the terminal

2. The navigate to the git repository.

3. once there type the following commands:

```terminal
git checkout --orphan latest_branch
git add -A
git commit -am "commit message"
git branch -D main
git branch -m main
git push -f origin main
```
credits to [marsnebulasoup](https://stackoverflow.com/users/8402369/marsnebulasoup) and [Desta Haileselassie Hagos](https://stackoverflow.com/users/1731796/desta-haileselassie-hagos)

