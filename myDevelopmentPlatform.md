Starting from a new Mac

1. Software Update
2. Chrome
3. Chrome Canary
4. xCode command line tools
5. Sublime Text 3
	create a ~/bin
	add subl to it
	create a .bash_profile
	add to bath
	add 'package control'
	- Color Highlighter
	- Sublimelinter
	- BracketHighlighter
	- Alignment
	
6. iTerm2
	Solarized theme https://github.com/altercation/solarized/tree/master/iterm2-colors-solarized
	Menlo font

7. homebrew
	`$ echo 'export PATH="/usr/local/bin:$PATH"' >> ~/.bash_profile`
	` brew doctor`
8. quicklook plugins: https://github.com/sindresorhus/quick-look-plugins 
	`brew cask install qlcolorcode qlstephen qlmarkdown quicklook-json qlprettypatch quicklook-csv betterzipql qlimagesize webpquicklook suspicious-package` 
9. Google drive 
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

	`touch ~/.gitignore`
	Use global .gitignore in github gist

11. `brew install mysql`
	mysql_secure_installation //mimic production environmnent
	add to the auto load
	`ln -sfv /usr/local/opt/mysql/*.plist ~/Library/LaunchAgents`

12. python
	`brew install pyenv
	install python 3.5.1
	`pyenv global 3.5.1
	install python 2.7.11
	`pip install --upgrade setuptools
	`pip install --upgrade pip
	`pip install virtualenv

	for both versions

13. `brew install gcc
	`pip install nose
	`pip install pyparsing
	`pip install python-dateutil
	`pip install pep8
	`pip install numpy
	`pip install scipy
	`pip install matplotlib
	`pip install ipython[all]

	Everything else install with virtualenv

14. Sequel Pro
15. iStats ??? license may be per computer
16. `brew install node
	# for sublimelinter
	`npm install -g csslint
	`npm install -g jshint
	`pip install pylint
17. Gulp
	`npm install --global gulp-cli
18. Grunt
	`sudo npm install --global grunt-cli
19. `brew install imagemagick`
20. Amazon Web Services command line interface
21. `npm install -g bower`
22. `pip install pandas`
23. anaconda
24. autoenv #used to automatically start virtual environment everytime I enter directory
