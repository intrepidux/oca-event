=================================================
Online event ticket sales with alternative prices
=================================================

.. !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-LGPL--3-blue.png
    :target: http://www.gnu.org/licenses/lgpl-3.0-standalone.html
    :alt: License: LGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fevent-lightgray.png?logo=github
    :target: https://github.com/OCA/event/tree/15.0/website_event_sale_b2x_alt_price
    :alt: OCA/event
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/event-15-0/event-15-0-website_event_sale_b2x_alt_price
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runbot-Try%20me-875A7B.png
    :target: https://runbot.odoo-community.org/runbot/199/15.0
    :alt: Try me on Runbot

|badge1| |badge2| |badge3| |badge4| |badge5| 

This module extends the functionality of website event sales to support
displaying the alternative price in the website event registration page and to
allow your visitors to know the final price in case they will have some special
fiscal tax behavior.

**Table of contents**

.. contents::
   :local:

Usage
=====

To use this module, you need to:

#. Configure some tickets for your event.
#. The product associated with the tickets should have taxes.
#. Publish the event.

Known issues / Roadmap
======================

* When the public pricelist is set to display discounts in customer's face and
  the website is set to display prices tax included, the discounted price will
  appear always as tax excluded and produce weird scenarios. This is Odoo's
  bug and not this module's. It has been notified as OPW-2518694 but it doesn't
  look like it's going to be fixed any soon. In v16, event price discounts from
  pricelist don't even work and for v17 there's an ongoing refactoring work.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/event/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us smashing it by providing a detailed and welcomed
`feedback <https://github.com/OCA/event/issues/new?body=module:%20website_event_sale_b2x_alt_price%0Aversion:%2015.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Tecnativa

Contributors
~~~~~~~~~~~~

* `Tecnativa <https://www.tecnativa.com>`_:

  * Jairo Llopis
  * Carlos Roca
  * David Vidal

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

.. |maintainer-Yajo| image:: https://github.com/Yajo.png?size=40px
    :target: https://github.com/Yajo
    :alt: Yajo

Current `maintainer <https://odoo-community.org/page/maintainer-role>`__:

|maintainer-Yajo| 

This module is part of the `OCA/event <https://github.com/OCA/event/tree/15.0/website_event_sale_b2x_alt_price>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
