collective.publications Installation
------------------------------------

To install collective.publications using zc.buildout and the plone.recipe.zope2instance
recipe to manage your project, you can do this:

* Add ``collective.publications`` to the list of eggs to install, e.g.:

    [buildout]
    ...
    eggs =
        ...
        collective.publications
       
* Re-run buildout, e.g. with:

    $ ./bin/buildout
