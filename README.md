Both `pylint.el` and `epylint.py` used to be maintained in the
[pylint repository](https://github.com/pylint-dev/pylint), they
are now both mentained in this repository instead.  As before,
the `pylint` package on Melpa, contains both of these files.
There are no plans to change that.

If, for some reason, you are using `epyling.py` but not `pylint.el`,
then you now have to install the Emacs `pylint` package from Melpa,
while previously you could install just Python `pylint`.

For more information about why these files were moved out of the
pylint repository, see https://github.com/pylint-dev/pylint/issues/7737.
