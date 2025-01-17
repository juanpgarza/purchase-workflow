=============================
Purchase Order Secondary Unit
=============================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:3759ed569394b34e6d79a9dfe97979e007b624be6c9557fa09ec3aa2511dc5fd
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fpurchase--workflow-lightgray.png?logo=github
    :target: https://github.com/OCA/purchase-workflow/tree/17.0/purchase_order_secondary_unit
    :alt: OCA/purchase-workflow
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/purchase-workflow-17-0/purchase-workflow-17-0-purchase_order_secondary_unit
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/purchase-workflow&target_branch=17.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

This module extends the functionality of purchase orders to allow buy
products in secondary unit of distinct category.

**Table of contents**

.. contents::
   :local:

Usage
=====

To use this module you need to:

1. Go to a *Product > General Information tab*.
2. Create any record in "Secondary unit of measure".
3. Set the conversion factor.
4. Go to *Purchase > Quotation > Create*.
5. Change secondary qty and secondary uom in line, and quantity
   (product_qty) will be changed (according to the conversion factor).

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/purchase-workflow/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/purchase-workflow/issues/new?body=module:%20purchase_order_secondary_unit%0Aversion:%2017.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
-------

* Tecnativa

Contributors
------------

- `Tecnativa <https://www.tecnativa.com>`__:

  - Sergio Teruel
  - Ernesto Tejeda

- Nikul Chaudhary <nikulchaudhary2112@gmail.com>
- Pimolnat Suntian <pimolnats@ecosoft.co.th>
- Miguel Ángel Gómez <miguel.gomez@braintec.com>

Maintainers
-----------

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

This module is part of the `OCA/purchase-workflow <https://github.com/OCA/purchase-workflow/tree/17.0/purchase_order_secondary_unit>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
