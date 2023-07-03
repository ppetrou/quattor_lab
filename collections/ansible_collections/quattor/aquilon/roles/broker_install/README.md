quattor.aquilon.broker_install
=========

Installs an Aquilon Broker

This role targets to provision dev aquilon brokers. For production deployments it has to be reviewed for suitability and adapted if needed.

Requirements
------------

The hostname of the aquillon node must be a FQDN.


Role Variables
--------------

|Variable|Level|Type|Description
|---|---|---|---
|quattor_ver|default|string|The quattor version to install. Must match the repo directory name in http://yum.quattor.org/
|default_org|default|string|The Organization Name


Dependencies
------------

NA

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: aquillon_broker
      roles:
         - role: quattor.aquilon.broker_install
           vars:
             quattor_ver: 21.4.0
             default_org: MyOrg

License
-------

Apache 2.0

Author Information
------------------

Petros Petrou
www.petrospetrou.co.uk
ppetrou@gmail.com

