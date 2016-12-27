

# prj007

Hello World!

This is my first project in GitHub :)

-007

Example workflow for PR:
http://singularity.lbl.gov/contributing-code

update .git/config with upstream repo info:
```
[remote "upstream"]
        url = https://github.com/ppc007/prj007
        fetch = +refs/heads/*:refs/remotes/origin/*
```

```bash
git checkout master
git pull upstream master	# pull updates from upstream into my master repo.
git push origin master		# really just update my fork.  PR need to be done via web?
                        	# really same as just vanilla git push ?
```



here is a random insignificant change, added to create a PR conflict, 
going test git pull --rebase...

going, really going crazy now.
tin6150 did a pull --rebase, created PR that can be merged automatically.
but after getting the PR, but before accepting/merging it, 
made this change to README.md 
conflict galore? :)

## summary

overall, seems that when working on a forked branch, 
run 
`git pull upstream master`, 
`git pull --rebase`
and make sure all changes looks good locally.
then run `git commit` and `git push` to my own git master.
at this point, creating a PR with upstream should produce a PR that can be merged automatically w/o conflicts.

