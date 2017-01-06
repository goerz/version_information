%version_information
====================

IPython magic extension for showing version information for dependency modules
in a notebook.

See the
[example notebook](http://nbviewer.ipython.org/urls/raw.github.com/goerz/version_information/master/example.ipynb)
for an example of how to use this magic extension.

This is a personalized fork of
[jrjohansson/version_information](https://github.com/jrjohansson/version_information).
Its main extra feature is that is allows to obtain version from commands, e.g.


    %version_information numpy, "vi --version", 'grep --version'


Installation
============

    pip install git+git://github.com/goerz/version_information.git


License
=======

This work is licensed under a [Creative Commons Attribution 3.0 Unported License.](http://creativecommons.org/licenses/by/3.0/)
