OpenStack pip install
#####################
:tags: openstack, pip, install, cloud, ansible
:category: \*nix

This role will install pip using the upstream pip.

.. code-block:: yaml

    - name: Install pip and lock it down
      hosts: host_name
      user: root
      roles:
        - role: "pip_install"
          pip_upstream_url: https://bootstrap.pypa.io/get-pip.py
          tags:
            - "pip-install"
