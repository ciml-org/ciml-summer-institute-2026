# Exercise 9: The `git pull` command

To update your copy of the GitHub repository, navigate to the `~/ciml-summer-institute-2026` directory and then run the `git pull` command. This will download all of the latest update from your instructors. 

*Command*
```
git pull
```

*Output*
```
[mkandes@login01 ciml-summer-institute-2026]$ git pull
remote: Enumerating objects: 43, done.
remote: Counting objects: 100% (43/43), done.
remote: Compressing objects: 100% (40/40), done.
remote: Total 40 (delta 29), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (40/40), 13.19 KiB | 5.00 KiB/s, done.
From https://github.com/ciml-org/ciml-summer-institute-2026
   288a42d..b58b2c4  main       -> origin/main
Updating 288a42d..b58b2c4
Fast-forward
 1.2_accounts_login_environment_expanse_portal/README.md | 190 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++-
 1 file changed, 189 insertions(+), 1 deletion(-)
[mkandes@login01 ciml-summer-institute-2026]$
```
