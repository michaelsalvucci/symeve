




I installed Symfony 2 as a submodule by doing this:

git init
git clone git://github.com/symfony/symfony.git lib/vendor/symfony
git submodule add git://github.com/symfony/symfony.git lib/vendor/symfony
git submodule foreach --recursive 'git submodule init && git submodule update'

