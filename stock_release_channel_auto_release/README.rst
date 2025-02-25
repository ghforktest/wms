==================================
Stock Release Channel Auto Release
==================================

.. !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fwms-lightgray.png?logo=github
    :target: https://github.com/OCA/wms/tree/16.0/stock_release_channel_auto_release
    :alt: OCA/wms
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/wms-16-0/wms-16-0-stock_release_channel_auto_release
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runbot-Try%20me-875A7B.png
    :target: https://runbot.odoo-community.org/runbot/285/16.0
    :alt: Try me on Runbot

|badge1| |badge2| |badge3| |badge4| |badge5| 

This addons define an automatic release mode on the release channels. By default
release channels manage the release of the transfers in batch mode. This means
that the transfers are released only when the user manually triggers the release
process by clicking on the release button.

When the automatic release mode is enabled, the transfers are released automatically
when a new transfer is added to the channel or as soon a product becomes available.

As for the batch mode, the automatic release process is only active on open channels.
When is locked, the automatic release process is stopped. Once the channel is unlocked,
the automatic release process is restarted and transfers into the channel are released
if they are ready to be released (IOW if quantities are available for moves not
yet released).

**Table of contents**

.. contents::
   :local:

Usage
=====

Use Inventory > Operations > Release Channels to access to the dashboard.

Edit a channel and select 'Automatic' into the list of available release mode.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/wms/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us smashing it by providing a detailed and welcomed
`feedback <https://github.com/OCA/wms/issues/new?body=module:%20stock_release_channel_auto_release%0Aversion:%2016.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* ACSONE SA/NV

Contributors
~~~~~~~~~~~~

* Laurent Mignon <laurent.mignon@acsone.eu>
* Jacques-Etienne Baudoux <je@bcim.be>

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

This module is part of the `OCA/wms <https://github.com/OCA/wms/tree/16.0/stock_release_channel_auto_release>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
