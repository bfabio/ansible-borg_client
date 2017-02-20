Getting started
===============

.. contents::
   :local:


Example inventory
-----------------

To enable the borg_client service on a host, it needs to be included in the
``[debops_service_borg_client]`` Ansible inventory group:

.. code-block:: none

   [debops_service_borg_client]
   hostname


Example playbook
----------------

If you are using this role without DebOps, here's an example Ansible playbook
that uses the ``debops.borg_client`` role:

.. literalinclude:: playbooks/borg_client.yml
   :language: yaml
