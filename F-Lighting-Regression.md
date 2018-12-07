# Investigation Regressions Efficiently using Git Bisect -John Blackborun @johnbillion

Bisect - to cut or divide into two equal parts

$ Git bisect start
$ Git bisect good "2.6.10" (using an existing tag as reference)
$ Git bisect bad HEAD

Bisecting: ## revisions left to test after this (roughly 6 steps)

Git brings up commit ½ way

$ git bisect bad/good (we respond with weather the "half" commit was good or bad, then Git goes to a new "half" commit depending on our response)

$ git diff ####goodcommithash. ####badcommithash

## We can do better
$ git bisect start -- path/to/code (limits to only specific files versus the full repository)