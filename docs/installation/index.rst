Installation
------------
.. note:: The library has been tested against Python 2.7 and 3.4+.


Installing from PyPi
^^^^^^^^^^^^^^^^^^^^
.. note:: This is the preferred installation method.

.. code-block:: console

    $ pip install django-map-widgets


Installing from source
^^^^^^^^^^^^^^^^^^^^^^
Alternatively, install the package from github

.. code-block:: console

    $ pip install git+git://github.com/erdem/django-map-widgets.git



Requirements
^^^^^^^^^^^^

Django map widgets uses the internal admins jQuery files. No further import is necessary. But if you use this in a djangoForm class then you should import your own jQuery during the frontend implementation of the widget.
