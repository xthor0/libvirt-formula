
Changelog
=========

`3.3.0 <https://github.com/saltstack-formulas/libvirt-formula/compare/v3.2.2...v3.3.0>`_ (2019-11-04)
---------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **release.config.js:** use full commit hash in commit link [skip ci] (\ `c179349 <https://github.com/saltstack-formulas/libvirt-formula/commit/c17934967c410cf7114dc48ade88968286edb6db>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen:** use ``debian-10-master-py3`` instead of ``develop`` [skip ci] (\ `d9e6736 <https://github.com/saltstack-formulas/libvirt-formula/commit/d9e673659c3e79f219c2c6042494c9a1ae2f85f6>`_\ )
* **kitchen:** use ``develop`` image until ``master`` is ready (\ ``amazonlinux``\ ) [skip ci] (\ `1450f7a <https://github.com/saltstack-formulas/libvirt-formula/commit/1450f7a2f6270722ec2d264dd646033bb8994c60>`_\ )
* **kitchen+travis:** upgrade matrix after ``2019.2.2`` release [skip ci] (\ `6828e08 <https://github.com/saltstack-formulas/libvirt-formula/commit/6828e087750c031a190ffc946eda843b5af86ba5>`_\ )
* **travis:** update ``salt-lint`` config for ``v0.0.10`` [skip ci] (\ `4b3c687 <https://github.com/saltstack-formulas/libvirt-formula/commit/4b3c687495dccf14d4aecaf8301a48503d20cc0c>`_\ )

Features
^^^^^^^^


* **config:** update libvirtd.conf jinja template to version 5.8.0 (\ `0c30455 <https://github.com/saltstack-formulas/libvirt-formula/commit/0c304553d4df4d5c85f83982cbec153326d8b43c>`_\ )

Performance Improvements
^^^^^^^^^^^^^^^^^^^^^^^^


* **travis:** improve ``salt-lint`` invocation [skip ci] (\ `061b269 <https://github.com/saltstack-formulas/libvirt-formula/commit/061b2695313cc6f03e9851e13abc1f084a254fb2>`_\ )

`3.2.2 <https://github.com/saltstack-formulas/libvirt-formula/compare/v3.2.1...v3.2.2>`_ (2019-10-14)
---------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **rubocop:** resolve ``Lint/AmbiguousRegexpLiteral`` (\ ` <https://github.com/saltstack-formulas/libvirt-formula/commit/e13085d>`_\ )

`3.2.1 <https://github.com/saltstack-formulas/libvirt-formula/compare/v3.2.0...v3.2.1>`_ (2019-10-14)
---------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **rubocop:** add an empty line after magic comments (\ ` <https://github.com/saltstack-formulas/libvirt-formula/commit/ca963fe>`_\ )
* **rubocop:** add empty line after guard clause (\ ` <https://github.com/saltstack-formulas/libvirt-formula/commit/1978566>`_\ )
* **rubocop:** avoid comma after the last item of a hash (\ ` <https://github.com/saltstack-formulas/libvirt-formula/commit/a8c5d31>`_\ )
* **rubocop:** do not prefix reader method names with get_ (\ ` <https://github.com/saltstack-formulas/libvirt-formula/commit/e7ced7b>`_\ )
* **rubocop:** extra empty line detected at block body end (\ ` <https://github.com/saltstack-formulas/libvirt-formula/commit/f4dcb5a>`_\ )
* **rubocop:** extra empty line detected at class body end (\ ` <https://github.com/saltstack-formulas/libvirt-formula/commit/fc0af73>`_\ )
* **rubocop:** favor modifier if usage when having a single-line body (\ ` <https://github.com/saltstack-formulas/libvirt-formula/commit/e3a9716>`_\ )
* **rubocop:** missing magic comment “frozen_string_literal: true” (\ ` <https://github.com/saltstack-formulas/libvirt-formula/commit/a07dbfb>`_\ )
* **rubocop:** prefer single-quoted strings and split too long line (\ ` <https://github.com/saltstack-formulas/libvirt-formula/commit/7944e24>`_\ )
* **rubocop:** remove “is_” prefix from predicate name (\ ` <https://github.com/saltstack-formulas/libvirt-formula/commit/c3d20bb>`_\ )
* **rubocop:** simplify complex methods (\ ` <https://github.com/saltstack-formulas/libvirt-formula/commit/2f6bb0e>`_\ )
* **rubocop:** the name of source file should use snake_case (\ ` <https://github.com/saltstack-formulas/libvirt-formula/commit/fde048a>`_\ )
* **rubocop:** unnecessary utf-8 encoding comment (\ ` <https://github.com/saltstack-formulas/libvirt-formula/commit/d605400>`_\ )
* **rubocop:** unused block argument (\ ` <https://github.com/saltstack-formulas/libvirt-formula/commit/7a0054c>`_\ )
* **rubocop:** unused method argument (\ ` <https://github.com/saltstack-formulas/libvirt-formula/commit/da0853a>`_\ )
* **rubocop:** use “.zero?” instead of “== 0” (\ ` <https://github.com/saltstack-formulas/libvirt-formula/commit/9108afb>`_\ )
* **rubocop:** use // around regular expression (\ ` <https://github.com/saltstack-formulas/libvirt-formula/commit/36f7d3d>`_\ )
* **rubocop:** use only ascii symbols in comments (\ ` <https://github.com/saltstack-formulas/libvirt-formula/commit/3edb35c>`_\ )
* **rubocop:** use the return of the conditional for variable assignment (\ ` <https://github.com/saltstack-formulas/libvirt-formula/commit/f57d9fb>`_\ )
* **rubocop:** when using method_missing, define respond_to_missing? (\ ` <https://github.com/saltstack-formulas/libvirt-formula/commit/b0227e2>`_\ )
* **rubocop:** when using method_missing, fall back on super (\ ` <https://github.com/saltstack-formulas/libvirt-formula/commit/db3d181>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* merge travis matrix, add ``salt-lint`` & ``rubocop`` to ``lint`` job (\ ` <https://github.com/saltstack-formulas/libvirt-formula/commit/18cef25>`_\ )
* merge travis matrix, add ``salt-lint`` & ``rubocop`` to ``lint`` job (\ ` <https://github.com/saltstack-formulas/libvirt-formula/commit/2b3acd6>`_\ )
* **travis:** enforce rubocop (\ ` <https://github.com/saltstack-formulas/libvirt-formula/commit/c7c5e57>`_\ )

Documentation
^^^^^^^^^^^^^


* **contributing:** remove to use org-level file instead [skip ci] (\ ` <https://github.com/saltstack-formulas/libvirt-formula/commit/a22c209>`_\ )
* **readme:** update link to ``CONTRIBUTING`` [skip ci] (\ ` <https://github.com/saltstack-formulas/libvirt-formula/commit/09d9a0c>`_\ )

`3.2.0 <https://github.com/saltstack-formulas/libvirt-formula/compare/v3.1.1...v3.2.0>`_ (2019-10-03)
---------------------------------------------------------------------------------------------------------

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen:** change ``log_level`` to ``debug`` instead of ``info`` (\ `198fe0b <https://github.com/saltstack-formulas/libvirt-formula/commit/198fe0b>`_\ )
* **kitchen:** install required packages to bootstrapped ``opensuse`` [skip ci] (\ `adb9004 <https://github.com/saltstack-formulas/libvirt-formula/commit/adb9004>`_\ )
* **kitchen:** use bootstrapped ``opensuse`` images until ``2019.2.2`` [skip ci] (\ `8bc62c7 <https://github.com/saltstack-formulas/libvirt-formula/commit/8bc62c7>`_\ )
* **platform:** add ``arch-base-latest`` (commented out for now) [skip ci] (\ `4ba9be5 <https://github.com/saltstack-formulas/libvirt-formula/commit/4ba9be5>`_\ )
* **yamllint:** add rule ``empty-values`` & use new ``yaml-files`` setting (\ `3e522e8 <https://github.com/saltstack-formulas/libvirt-formula/commit/3e522e8>`_\ )

Features
^^^^^^^^


* **tofs:** use TOFS to distribute configuration templates to minion (\ `8cd04f9 <https://github.com/saltstack-formulas/libvirt-formula/commit/8cd04f9>`_\ )

`3.1.1 <https://github.com/saltstack-formulas/libvirt-formula/compare/v3.1.0...v3.1.1>`_ (2019-09-09)
---------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **config:** libvirtd configuration changes must restart the service (\ `4d6f38e <https://github.com/saltstack-formulas/libvirt-formula/commit/4d6f38e>`_\ )

Code Refactoring
^^^^^^^^^^^^^^^^


* **config:** explicit package requisite (\ `8afec46 <https://github.com/saltstack-formulas/libvirt-formula/commit/8afec46>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* use ``dist: bionic`` & apply ``opensuse-leap-15`` SCP error workaround (\ `400d686 <https://github.com/saltstack-formulas/libvirt-formula/commit/400d686>`_\ )

`3.1.0 <https://github.com/saltstack-formulas/libvirt-formula/compare/v3.0.1...v3.1.0>`_ (2019-09-04)
---------------------------------------------------------------------------------------------------------

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen+travis:** check the clean states on develop salt (\ `0e735c0 <https://github.com/saltstack-formulas/libvirt-formula/commit/0e735c0>`_\ )

Documentation
^^^^^^^^^^^^^


* **readme:** explain the new “clean” states (\ `cceb4d3 <https://github.com/saltstack-formulas/libvirt-formula/commit/cceb4d3>`_\ )

Features
^^^^^^^^


* **clean:** add cleaning states (\ `dd53de0 <https://github.com/saltstack-formulas/libvirt-formula/commit/dd53de0>`_\ )

Tests
^^^^^


* **clean:** check for clean states (\ `0978ab0 <https://github.com/saltstack-formulas/libvirt-formula/commit/0978ab0>`_\ )
* **inspec:** share libraries between profiles (\ `6f816e0 <https://github.com/saltstack-formulas/libvirt-formula/commit/6f816e0>`_\ )

`3.0.1 <https://github.com/saltstack-formulas/libvirt-formula/compare/v3.0.0...v3.0.1>`_ (2019-09-02)
---------------------------------------------------------------------------------------------------------

Documentation
^^^^^^^^^^^^^


* **readme:** update for the new layout (\ `b9fabd3 <https://github.com/saltstack-formulas/libvirt-formula/commit/b9fabd3>`_\ )

`3.0.0 <https://github.com/saltstack-formulas/libvirt-formula/compare/v2.3.1...v3.0.0>`_ (2019-09-02)
---------------------------------------------------------------------------------------------------------

Code Refactoring
^^^^^^^^^^^^^^^^


* **states:** ids must conform to “template-formula” standard (\ `8adfe9e <https://github.com/saltstack-formulas/libvirt-formula/commit/8adfe9e>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen+travis:** replace EOL pre-salted images (\ `262c063 <https://github.com/saltstack-formulas/libvirt-formula/commit/262c063>`_\ )

Features
^^^^^^^^


* **cert:** key and certificate generation is a server sub component (\ `616b585 <https://github.com/saltstack-formulas/libvirt-formula/commit/616b585>`_\ )
* **config:** the configuration is a server sub component (\ `6dc318d <https://github.com/saltstack-formulas/libvirt-formula/commit/6dc318d>`_\ )
* **layout:** initialize the new top level layout (\ `886198b <https://github.com/saltstack-formulas/libvirt-formula/commit/886198b>`_\ )
* **packages:** dispatch package installation per component (\ `f9e587d <https://github.com/saltstack-formulas/libvirt-formula/commit/f9e587d>`_\ )
* **packages:** the python library is a dedicated component (\ `d07a3ec <https://github.com/saltstack-formulas/libvirt-formula/commit/d07a3ec>`_\ )
* **service:** service is a subcomponent of “libvirt.server” (\ `c51d2d2 <https://github.com/saltstack-formulas/libvirt-formula/commit/c51d2d2>`_\ )

BREAKING CHANGES
^^^^^^^^^^^^^^^^


* **states:** “libvirt.pkg” become “libvirt-server-package-install-pkg-installed”
* **layout:** the layout is completly modified for single state.apply
* **states:** “libvirt.daemonconfig” become “libvirt-server-config-files-daemonconfig-file-managed”
* **states:** “libvirt.service” become “libvirt-server-service-running-service-running”
* **states:** “libvirt.keys” become “libvirt-server-tls-certs-virt-keys”
* **states:** “libvirt-python” become “libvirt-python-install-pkg-install”
* **states:** “qemu” become “libvirt-qemu-install-pkg-installed”
* **states:** “libvirt.config” become “libvirt-server-config-files-libvirtd-file-managed”
* **cert:** the key is now libvirt.server.tls.certs
* **service:** the service is now libvirt.server.service.running
* **config:** the configuration is now libvirt.server.config.files
* **packages:** libvirt package is installed by libvirt.server.package.install
* **packages:** qemu package is installed by libvirt.qemu.install
* **packages:** extra packages are installed by libvirt.extra.install
* **states:** “extra_pkgs” become “libvirt-extra-install-pkg-installed”

`2.3.1 <https://github.com/saltstack-formulas/libvirt-formula/compare/v2.3.0...v2.3.1>`_ (2019-08-22)
---------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **packages:** centos does not have Python3 libvirt library (\ `b8b761c <https://github.com/saltstack-formulas/libvirt-formula/commit/b8b761c>`_\ )

`2.3.0 <https://github.com/saltstack-formulas/libvirt-formula/compare/v2.2.0...v2.3.0>`_ (2019-08-21)
---------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **config:** suse family does not have it's own configuration file (\ `a41f784 <https://github.com/saltstack-formulas/libvirt-formula/commit/a41f784>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **travis:** enable “default-opensuse-leap-15-2019-2-py3” platform (\ `3c2f4fa <https://github.com/saltstack-formulas/libvirt-formula/commit/3c2f4fa>`_\ )

Features
^^^^^^^^


* **suse:** add OS family packages and daemon configuration path (\ `72e6aea <https://github.com/saltstack-formulas/libvirt-formula/commit/72e6aea>`_\ )

Tests
^^^^^


* **inspec:** add openSUSE to supported platforms (\ `309e65a <https://github.com/saltstack-formulas/libvirt-formula/commit/309e65a>`_\ )

`2.2.0 <https://github.com/saltstack-formulas/libvirt-formula/compare/v2.1.0...v2.2.0>`_ (2019-08-10)
---------------------------------------------------------------------------------------------------------

Features
^^^^^^^^


* **yamllint:** include for this repo and apply rules throughout (\ `8030695 <https://github.com/saltstack-formulas/libvirt-formula/commit/8030695>`_\ )

`2.1.0 <https://github.com/saltstack-formulas/libvirt-formula/compare/v2.0.1...v2.1.0>`_ (2019-07-30)
---------------------------------------------------------------------------------------------------------

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **travis:** enable default-fedora-27-2017-7-py2 (\ `ef1f3de <https://github.com/saltstack-formulas/libvirt-formula/commit/ef1f3de>`_\ )

Features
^^^^^^^^


* **packages:** set dedicated python package names for Fedora (\ `b02ff7b <https://github.com/saltstack-formulas/libvirt-formula/commit/b02ff7b>`_\ )

Tests
^^^^^


* **inspec:** support Fedora (\ `604a803 <https://github.com/saltstack-formulas/libvirt-formula/commit/604a803>`_\ )

`2.0.1 <https://github.com/saltstack-formulas/libvirt-formula/compare/v2.0.0...v2.0.1>`_ (2019-07-30)
---------------------------------------------------------------------------------------------------------

Styles
^^^^^^


* **ruby:** improve Ruby coding style (\ `845556f <https://github.com/saltstack-formulas/libvirt-formula/commit/845556f>`_\ )

`2.0.0 <https://github.com/saltstack-formulas/libvirt-formula/compare/v1.0.0...v2.0.0>`_ (2019-07-29)
---------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **packages:** python2 libvirt library is unusable by Python3 minion (\ `e16bfad <https://github.com/saltstack-formulas/libvirt-formula/commit/e16bfad>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **travis:** enable default-ubuntu-1804-2019-2-py3 (\ `6679340 <https://github.com/saltstack-formulas/libvirt-formula/commit/6679340>`_\ )

Tests
^^^^^


* **inspec:** enable Ubuntu platform (\ `5ae997e <https://github.com/saltstack-formulas/libvirt-formula/commit/5ae997e>`_\ )
* **inspec:** python package name depends on Salt environnment (\ `5322aee <https://github.com/saltstack-formulas/libvirt-formula/commit/5322aee>`_\ )

BREAKING CHANGES
^^^^^^^^^^^^^^^^


* 
  **packages:** the Python2 package is now “python2_pkg”.

* 
  libvirt/python.sls: use “switch_python32” macro to select the python
  package and do nothing if it's not available.

* 
  libvirt/keys.sls: ditoo.

* 
  libvirt/python.jinja: new macro “switch_python32” to select one of
  the two arguments based on the environment of the SaltStack minion.

* 
  libvirt/defaults.yaml: distinguish python2 and python3 packages.

* 
  libvirt/osfamilymap.yaml (Debian): distinguish python2 and python3
  packages.

`1.0.0 <https://github.com/saltstack-formulas/libvirt-formula/compare/v0.7.0...v1.0.0>`_ (2019-07-21)
---------------------------------------------------------------------------------------------------------

Features
^^^^^^^^


* **map.jinja:** update to template standards (\ `b822a87 <https://github.com/saltstack-formulas/libvirt-formula/commit/b822a87>`_\ )

BREAKING CHANGES
^^^^^^^^^^^^^^^^


* 
  **map.jinja:** use “osfinger” instead of “oscodename” to override
  configuration per distribution version.

* 
  libvirt/map.jinja: update to “template-formula” standard.

* 
  libvirt/osfamilymap.yaml: fix the name for the “os_family” settings.

* 
  libvirt/osmap.yaml: empty per OS name settings for now.

* 
  libvirt/osfingermap.yaml: replace “oscodename” overrides.
  Set some settings for older Debian and Ubuntu releases.

`0.7.0 <https://github.com/saltstack-formulas/libvirt-formula/compare/v0.6.0...v0.7.0>`_ (2019-07-15)
---------------------------------------------------------------------------------------------------------

Documentation
^^^^^^^^^^^^^


* **readme:** update headings and add for ``inspec`` as well (\ `df62ff2 <https://github.com/saltstack-formulas/libvirt-formula/commit/df62ff2>`_\ )

Features
^^^^^^^^


* **semantic-release:** implement an automated changelog (\ `7c81125 <https://github.com/saltstack-formulas/libvirt-formula/commit/7c81125>`_\ )

Tests
^^^^^


* **kitchen+inspec:** comply with template-formula standards (\ `41ec6ce <https://github.com/saltstack-formulas/libvirt-formula/commit/41ec6ce>`_\ )
