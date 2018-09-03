.. _ImagingProcedures:

Imaging Procedures
==================



Imaging Meetings
^^^^^^^^^^^^^^^^

Neuroimaging meetings are held every other Thursday at 1p in the large 7SE meeting room.  The upcoming schedule can be found 
`here <https://docs.google.com/spreadsheets/d/1hSX8JcOFA1O8kVS_uniI5mVf9O0CYan_39BvsPlBqMw/edit?usp=sharing]>`_


Scanning Procedures
^^^^^^^^^^^^^^^^^^^

The basic order of things to do for a scan are: 

* book the `scanner <https://fmrif.nimh.nih.gov/internal/schedule>`_
* request a tech a week before the scan `here <https://fmrif.nimh.nih.gov/techs_form>`_ or use :ref:`TechRequests`, my script that will keep track of things and do it for you

* Scanning Procedures for each protocol are found on the `Imaging Sharepoint <https://nimhirpshare.nimh.nih.gov/sites/ETPB/imaging/>`_ `here <https://nimhirpshare.nimh.nih.gov/sites/ETPB/imaging/_layouts/15/start.aspx#/Shared%20Documents/Forms/AllItems.aspx?RootFolder=%2Fsites%2FETPB%2Fimaging%2FShared%20Documents%2FScanning%20Documents&FolderCTID=0x012000933BA55A87103248AB7BDB49F15518A8&View=%7BD3ADD2BA-90F2-49F8-9EAE-55DA9757F6EB%7D>`_

* When the scan is completed remember to

  * add the CRIS note
  * transfer the data 

.. _TechRequests:

Automagic Tech Requests
^^^^^^^^^^^^^^^^^^^^^^^


Running and checking on the tech request script (on felix)
.. code-block:: console

   python /data/MoodGroup/code/req_tech.py

It should ask a bunch of questions (same as `this form <https://fmrif.nimh.nih.gov/techs_form>`_). It’s important to fill out the information correctly (format wise), particularly the dates (spacing, abbreviation) as the program uses it to figure out when to send the email.

It should spit out a line giving you a job number and a send date/time. To check on the program type
.. code-block:: console

   atq

which will give you a list of the dates/times things will be sent or if you need to remove the email if the scan was cancelled 
.. code-block:: console

   atrm THEJOBNUMBER

get the job number from atq The atq list is specific to helix or felix, so remember which one you used (or always use the same one).


Data Procedures
===============


