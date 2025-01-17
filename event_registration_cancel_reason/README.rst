=============================================
Reasons for event registrations cancellations
=============================================

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
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fevent-lightgray.png?logo=github
    :target: https://github.com/OCA/event/tree/15.0/event_registration_cancel_reason
    :alt: OCA/event
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/event-15-0/event-15-0-event_registration_cancel_reason
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runbot-Try%20me-875A7B.png
    :target: https://runbot.odoo-community.org/runbot/199/15.0
    :alt: Try me on Runbot

|badge1| |badge2| |badge3| |badge4| |badge5| 

This module allows to add predefined reasons for the attendees to report back
why they cancel their registration to an event.

**Table of contents**

.. contents::
   :local:

Configuration
=============

To configure this module, you need to:

#. Go to **Events > Configuration > Registrations cancellation reasons** for setting the possible reasons you want to handle.

You can also set if a reason
is only available for certain types of events or if you leave it empty, for
all.

Usage
=====

#. Go to **Events > Events**
#. Enter into the details of any of the events.
#. Press the button "Attendees", located at the top right hand corner.
#. Press the red button in the right part of any of the registrations.
#. A new screen will appear asking you to enter the reason why the registration is cancelled.

You will get also the same screen:

#. Go to **Events > Reporting > Attendees (view list)**.
#. Enter into the details of any of the attendees.
#. Press the button *Cancel registration*.

On this object, you can group by the cancellation reason in the list, calendar or graph view.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/event/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us smashing it by providing a detailed and welcomed
`feedback <https://github.com/OCA/event/issues/new?body=module:%20event_registration_cancel_reason%0Aversion:%2015.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Tecnativa

Contributors
~~~~~~~~~~~~

* `Tecnativa <https://www.tecnativa.com>`__:

  * Rafael Blasco
  * Pedro M. Baeza
  * Vicent Cubells
  * Cristina Martín
  * Victor M.M. Torres
  * Víctor Martínez

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

This module is part of the `OCA/event <https://github.com/OCA/event/tree/15.0/event_registration_cancel_reason>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
