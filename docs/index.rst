.. toctree::
  :maxdepth: 0
  :hidden:
  :caption: gcloud

  gcloud-api
  gcloud-auth

.. toctree::
  :maxdepth: 0
  :hidden:
  :caption: Pub/Sub

  pubsub-usage
  Client <pubsub-client>
  pubsub-topic
  pubsub-subscription
  pubsub-message
  pubsub-iam

.. toctree::
  :maxdepth: 0
  :hidden:
  :caption: External Links

  GitHub <https://github.com/GoogleCloudPlatform/gcloud-python/>
  Issues <https://github.com/GoogleCloudPlatform/gcloud-python/issues>
  Stack Overflow <http://stackoverflow.com/questions/tagged/gcloud-python>
  PyPI <https://pypi.python.org/pypi/gcloud>

Getting started
---------------

The ``gcloud`` library is ``pip`` install-able:

.. code-block:: console

    $ pip install gcloud

If you have trouble installing
``pycrypto`` or ``pyopenssl``
(and you're on Ubuntu),
you can try install the precompiled packages:

.. code-block:: console

    $ sudo apt-get install python-crypto python-openssl

If you want to install everything with ``pip``,
try installing the ``dev`` packages beforehand:

.. code-block:: console

    $ sudo apt-get install python-dev libssl-dev

If you want to install ``gcloud-python`` from source,
you can clone the repository from GitHub:

.. code-block:: console

    $ git clone git://github.com/GoogleCloudPlatform/gcloud-python.git
    $ cd gcloud-python
    $ python setup.py install

----