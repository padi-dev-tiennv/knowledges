git process

- reset commit to root commit

  ```bash
  git reset 52092262e0d41da52dc1c31f03da7e54fe539dc7
  ```

- commit sepate source

  each code change will have separate commition

- git diff with origin

  ```bash
  git diff fix/BE/enable-donate-comment..origin/BE/enable-donate-comment 
  git push -f
  ```

  

- check out to current brank

  ```bash
  git checkout fix/BE/enable-donate-comment
  ```

- Always rebase from development

	```bash
	git diff fix/BE/enable-donate-comment..origin/BE/enable-donate-comment 
	
	git rebase -r development
	
	git push -f
	```
	
	