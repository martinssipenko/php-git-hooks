Git pre-commit hook for checking php syntax and coding standards
----------------------------------------------------------------

Requirements
============
- PHP CLI
- CodeSniffer (https://github.com/squizlabs/PHP_CodeSniffer)
- `phpcs.xml` file in your repository root

Setup
=====
Clone this repo to you home dir:

`git clone https://github.com/martinssipenko/php-git-pre-commit-hook.git /home/<username>/php-git-pre-commit-hook`
	
Allow file to be executed:

`chmod /home/<username>/php-git-pre-commit-hook/pre-commit`
	
Create a symlink:

`ln -s /home/<username>/php-git-pre-commit-hook/pre-commit /home/<username>/<you_repo>/.git/hooks/pre-commit`

Notes
=====
This script runs only on unix, feel free to modify.