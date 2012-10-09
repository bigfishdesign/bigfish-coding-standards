### Big Fish coding standards

These are the Big Fish coding standards, for use with CodeSniffer;
they're based on [Chris Adams's WordPress coding
standards](https://github.com/mrchrisadams/WordPress-Coding-Standards),
but with our own tweaks.

### How to use this 

Once you've installed PEAR, install CodeSniffer:

    pear install --alldeps PHP_CodeSniffer

Then install our coding standards:

    git clone git://github.com/robmiller/bigfish-coding-standards.git $(pear config-get php_dir)/PHP/CodeSniffer/Standards/BigFish

