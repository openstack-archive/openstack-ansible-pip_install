pip_install role docs
=====================

This role will install pip using the upstream pip. Within the installation
of pip the role will create a .pip directory within the deploying users
home folder and and blank selfcheck JSON file for pip to use to keep track
of versions.


Basic Role Example
^^^^^^^^^^^^^^^^^^

.. code-block:: yaml

    - role: "pip_install"
