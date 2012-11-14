Git pre-commit & commit-msg hooks
---------------------------------

- pre-commit - for checking php syntax and coding standards
- commit-msg - for checking if commit message contains issue number

Requirements
============
- PHP CLI
- CodeSniffer (https://github.com/squizlabs/PHP_CodeSniffer)
- `phpcs.xml` file in your repository root

Setup
=====
Clone this repo to you home dir:

`git clone https://github.com/martinssipenko/php-git-hooks.git /home/<username>/php-git-hooks`
	
Allow files to be executed:

`chmod -R +x /home/<username>/php-git-hooks/`
	
Create a symlinks:

`ln -s /home/<username>/php-git-hooks/pre-commit /home/<username>/<you_repo>/.git/hooks/pre-commit`
`ln -s /home/<username>/php-git-hooks/commit-msg /home/<username>/<you_repo>/.git/hooks/commit-msg`

Notes
=====
This script runs only on unix, feel free to modify.