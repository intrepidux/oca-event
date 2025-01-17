====================
Event Email Reminder
====================

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
    :target: https://github.com/OCA/event/tree/15.0/event_email_reminder
    :alt: OCA/event
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/event-15-0/event-15-0-event_email_reminder
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runbot-Try%20me-875A7B.png
    :target: https://runbot.odoo-community.org/runbot/199/15.0
    :alt: Try me on Runbot

|badge1| |badge2| |badge3| |badge4| |badge5| 

This module extends the functionality of event module to allow to send events
reminder emails before an event start.

**Table of contents**

.. contents::
   :local:

Configuration
=============

You can use cron arguments to modify three options in this position
(days, near_events, template_id):

* *days*: Change days to limit events search, 7 as default.
* *draft_events*: This is for including draft events also.
* *near_events*: Select an option to include events which begin date is between
  today and limit days, False as default.
* *template_id*: You can select and id template to render as third parameter,
  None by default, so email is rendered with the template installed by
  the module.
* partner_ids: By default, the event is notified to the event responsible, but
  you can choose who to notify indicating in this parameter a list of the IDs.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/event/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us smashing it by providing a detailed and welcomed
`feedback <https://github.com/OCA/event/issues/new?body=module:%20event_email_reminder%0Aversion:%2015.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Tecnativa

Contributors
~~~~~~~~~~~~

* Tecnativa <https://www.tecnativa.com>:

  * Sergio Teruel
  * Vicent Cubells
  * Pedro M. Baeza
  * Jairo Llopis
  * Víctor Martínez

Other credits
~~~~~~~~~~~~~

* Odoo Community Association: `Icon <https://github.com/OCA/maintainer-tools/blob/master/template/module/static/description/icon.svg>`_.

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

This module is part of the `OCA/event <https://github.com/OCA/event/tree/15.0/event_email_reminder>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
