Starting from a new Mac

1. Software Update
2. Chrome
3. Chrome Canary
4. xCode command line tools
	
6. iTerm2
	Solarized theme https://github.com/altercation/solarized/tree/master/iterm2-colors-solarized
	Menlo font

7. homebrew
	`$ echo 'export PATH="/usr/local/bin:$PATH"' >> ~/.bash_profile`
	` brew doctor`
10. git 
	set global user 
	set global password 
	`$ git config --global user.name "Your Name Here"`
	`$ git config --global user.email "your_email@youremail.com"` 
	`$ git config --global credential.helper osxkeychain `
	Set up Sublime as the Git merge tool 
	``` 
	$ git config --global mergetool.sublime.cmd "subl -w \$MERGED"
	$ git config --global mergetool.sublime.trustExitCode false 
	$ git config --global merge.tool sublime
	$ git mergetool -y
	```

