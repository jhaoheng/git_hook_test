## README

1. ```cd git_hook_test```
2. ```git clone server/repo.git project```
3. do an example

	```
	echo "test3" >> test3.log
	git add .
	git commit -m "add test3.log"
	git push origin master
	```
4. go to ```server/deploy``` , watch file change!!
	
## git hook use post-receive
path : server/repo.git/hooks/

--work-tree : deploy position
--git-dir : git.bare position

** remeber : checkout -f

## what you can play

1. edit 'origin' -> 'deploy'
2. try another hooks