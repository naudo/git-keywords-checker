Git Keywords Checker
====================
About
-----

This git hook  will automatically check your code for common oversights like `var_dump()`, `die()` or `console.log()` and stop you from commiting them into source control.


Installation
------------

To install this hook, copy the pre-commit file to your project's hooks folder.

    $ cp pre-commit .git/hooks/pre-commit;
    $ chmod +x .git/hooks/pre-commit;


Contact
-------
Forked from the version written by *Boris Guéry*

License
-------

See `COPYING`

