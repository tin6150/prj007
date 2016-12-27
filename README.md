

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
git pull upstream master
git push origin master		# really just update my fork.  PR need to be done via web?
				# really same as just vanilla git push ?

```


