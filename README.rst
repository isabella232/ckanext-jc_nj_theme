.. You should enable this project on travis-ci.org and coveralls.io to make
   these badges work. The necessary Travis and Coverage config files have been
   generated for you.

.. image:: https://travis-ci.org/Ontodia/ckanext-jc_nj_theme.svg?branch=master
    :target: https://travis-ci.org/Ontodia/ckanext-jc_nj_theme

.. image:: https://coveralls.io/repos/Ontodia/ckanext-jc_nj_theme/badge.png?branch=master
  :target: https://coveralls.io/r/Ontodia/ckanext-jc_nj_theme?branch=master

.. image:: https://pypip.in/download/ckanext-jc_nj_theme/badge.svg
    :target: https://pypi.python.org/pypi//ckanext-jc_nj_theme/
    :alt: Downloads

.. image:: https://pypip.in/version/ckanext-jc_nj_theme/badge.svg
    :target: https://pypi.python.org/pypi/ckanext-jc_nj_theme/
    :alt: Latest Version

.. image:: https://pypip.in/py_versions/ckanext-jc_nj_theme/badge.svg
    :target: https://pypi.python.org/pypi/ckanext-jc_nj_theme/
    :alt: Supported Python versions

.. image:: https://pypip.in/status/ckanext-jc_nj_theme/badge.svg
    :target: https://pypi.python.org/pypi/ckanext-jc_nj_theme/
    :alt: Development Status

.. image:: https://pypip.in/license/ckanext-jc_nj_theme/badge.svg
    :target: https://pypi.python.org/pypi/ckanext-jc_nj_theme/
    :alt: License

=============
ckanext-jc_nj_theme
=============

.. Put a description of your extension here:
   What does it do? What features does it have?
   Consider including some screenshots or embedding a video!


------------
Requirements
------------

For example, you might want to mention here which versions of CKAN this
extension works with.


------------
Installation
------------

.. Add any additional install steps to the list below.
   For example installing any non-Python dependencies or adding any required
   config settings.

To install ckanext-jc_nj_theme:

1. Activate your CKAN virtual environment, for example::

     . /usr/lib/ckan/default/bin/activate

2. Install the ckanext-jc_nj_theme Python package into your virtual environment::

     git clone https://github.com/Ontodia/ckanext-jc_nj_theme.git
     cd ckanext-jc_nj_theme
     python setup.py develop

3. Add ``jc_nj_theme`` to the ``ckan.plugins`` setting in your CKAN
   config file (by default the config file is located at
   ``/etc/ckan/default/production.ini``).

4. Restart CKAN. For example if you've deployed CKAN with Apache on Ubuntu::

     sudo service apache2 reload


---------------
Config Settings
---------------

Document any optional config settings here. For example::

    # The minimum number of hours to wait before re-checking a resource
    # (optional, default: 24).
    ckanext.jc_nj_theme.some_setting = some_default_value


-----------------
Running the Tests
-----------------

To run the tests, do::

    nosetests --nologcapture --with-pylons=test.ini

To run the tests and produce a coverage report, first make sure you have
coverage installed in your virtualenv (``pip install coverage``) then run::

    nosetests --nologcapture --with-pylons=test.ini --with-coverage --cover-package=ckanext.jc_nj_theme --cover-inclusive --cover-erase --cover-tests
