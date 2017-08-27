In the pelicanconf.py:

MARKUP = ('md', 'ipynb')

PLUGIN_PATHS = ['./plugins']
PLUGINS = ['ipynb.markup']


git init
git submodule add https://github.com/danielfrg/pelican-ipynb.git
