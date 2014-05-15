# Perl Virtualenvwrapper Hooks

This bunch of scripts provides a set of virtualenvwrapper hooks which allow a virtual environment to contain its own Perl libraries. At present it simply configures CPAN, installs local::lib, then uses CPAN to install a bunch of modules that I use regularly.

What you see in this repository is a direct import from my working system. My plan is to clean this repository up by splitting out my own "virtualenv hooks" modification (i.e.: use directories full of independent scripts) and leaving this repository with only the bits necessary for Perl support.

Feel free to email Alex Satrapa <grail@goldweb.com.au> or send me a push request through GitHub if you have changes that would be useful to either of my goals for this project.

# License

See the included LICENSE document.
