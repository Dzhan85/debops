|debops_logo| DebOps Contrib playbooks
======================================

Ansible playbooks to run `DebOps Contrib <https://github.com/debops-contrib/debops-contrib>`_ roles.

Here are a few services that are available
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**DNS and Networking**

+-------------+----------+------+
| apt_cacher_ | dnsmasq_ | tor_ |
+-------------+----------+------+

**Fully loaded ready to go applications**

+-----------+-----------+----------------+-------+---------------+
| bitcoind_ | foodsoft_ | homeassistant_ | kodi_ | volkszaehler_ |
+-----------+-----------+----------------+-------+---------------+

**Security**

+-----------+---------------------+-----------+
| AppArmor_ | dropbear-initramfs_ | Firejail_ |
+-----------+---------------------+-----------+

**Service monitoring and logging**

+-------------------+
| `Check_MK agent`_ |
+-------------------+

**System**

+--------+-------+---------------------+
| BTRFS_ | FUSE_ | `snapshot snapper`_ |
+--------+-------+---------------------+

**Workstations and clients**

+----------------+
| `X2Go Server`_ |
+----------------+

.. |debops_logo| image:: http://debops.org/images/debops-small.png

.. _apt_cacher: https://github.com/debops/debops/tree/master/ansible/debops-contrib-playbooks/service/apt_cacher.yml
.. _tor: https://github.com/debops/debops/tree/master/ansible/debops-contrib-playbooks/service/tor.yml
.. _dnsmasq: https://github.com/debops/debops/tree/master/ansible/debops-contrib-playbooks/service/dnsmasq.yml

.. _bitcoind: https://github.com/debops/debops/tree/master/ansible/debops-contrib-playbooks/service/bitcoind.yml
.. _foodsoft: https://github.com/debops/debops/tree/master/ansible/debops-contrib-playbooks/service/foodsoft.yml
.. _homeassistant: https://github.com/debops/debops/tree/master/ansible/debops-contrib-playbooks/service/homeassistant.yml
.. _kodi: https://github.com/debops/debops/tree/master/ansible/debops-contrib-playbooks/service/kodi.yml
.. _volkszaehler: https://github.com/debops/debops/tree/master/ansible/debops-contrib-playbooks/service/volkszaehler.yml

.. _AppArmor: https://github.com/debops/debops/tree/master/ansible/debops-contrib-playbooks/service/apparmor.yml
.. _dropbear-initramfs: https://github.com/debops/debops/tree/master/ansible/debops-contrib-playbooks/service/dropbear_initramfs.yml
.. _Firejail: https://github.com/debops/debops/tree/master/ansible/debops-contrib-playbooks/service/firejail.yml

.. _`Check_MK agent`: https://github.com/debops/debops/tree/master/ansible/debops-contrib-playbooks/service/checkmk_agent.yml

.. _BTRFS: https://github.com/debops/debops/tree/master/ansible/debops-contrib-playbooks/service/btrfs.yml
.. _FUSE: https://github.com/debops/debops/tree/master/ansible/debops-contrib-playbooks/service/fuse.yml
.. _`snapshot snapper`: https://github.com/debops/debops/tree/master/ansible/debops-contrib-playbooks/service/snapshot_snapper.yml

.. _X2Go Server: https://github.com/debops/debops/tree/master/ansible/debops-contrib-playbooks/service/x2go_server.yml
