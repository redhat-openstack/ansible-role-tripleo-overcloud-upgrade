Running an upgrade
==================


In order to run the upgrade you follow these steps

Pre undercloud upgrade tasks
----------------------------

.. include:: upgrade-undercloud-repo.rst

Followed by cleaning the yum cache ::

    sudo yum clean all

Undercloud upgrade
------------------

.. include:: undercloud-upgrade.rst

Pre overcloud upgrade tasks
---------------------------

Overcloud upgrade
-----------------

.. include:: overcloud-upgrade.rst


The files needed to the upgrade if any are the following:

.. include:: custom-templates.rst


Post overcloud upgrade
----------------------




