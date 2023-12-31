=========================
Employee Shift Scheduling
=========================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:2b3927874bab00c9713a5b7d8e54d881091c2f1a7bd24ad77617bc3aeeab9589
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-trevi--software%2Ftrevi--hr-lightgray.png?logo=github
    :target: https://github.com/trevi-software/trevi-hr/tree/14.0/resource_schedule
    :alt: trevi-software/trevi-hr

|badge1| |badge2| |badge3|

Easily create, manage, and track employee shift planning.

#. Work Detail Templates - templates describe a shift for one day. For example: 8 a.m to 5 p.m.
#. Work Detail - the Odoo record for describing a day in a Work Time. These records can get their settings from a Work Detail Template.
#. Work Time - the Odoo record for describing a weekly schedule.
#. Shift Schedule - the actual times that an employee is scheduled to work on a specific day.
#. Schedule Area - the area the employee is assigned to for a shift. For example, in a hotel with multiple dinning rooms all serving staff may have the same shifts but be assigned to different dinning rooms.
#. Schedule Group - schedule groups allow an organization to split employees into groups. Schedule groups can have their own work detail templates and managers who are responsible for managing shifts.

**Table of contents**

.. contents::
   :local:

Known issues / Roadmap
======================

* When demo data is enabled and the module is updated you may encounter and error the the demo data failed to install. This error may safely be ignored.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/trevi-software/trevi-hr/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/trevi-software/trevi-hr/issues/new?body=module:%20resource_schedule%0Aversion:%2014.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* TREVI Software
* Michael Telahun Makonnen

Other credits
~~~~~~~~~~~~~

* Michael Telahun Makonnen <mtm@trevi.et>

Maintainers
~~~~~~~~~~~

This module is part of the `trevi-software/trevi-hr <https://github.com/trevi-software/trevi-hr/tree/14.0/resource_schedule>`_ project on GitHub.

You are welcome to contribute.
