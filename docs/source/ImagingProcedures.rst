.. _ImagingProcedures:


Automagic Tech Requests
-----------------------

Running and checking on the tech request script (on felix)::

   python /data/MoodGroup/code/req_tech.py

It should ask a bunch of questions (same as `this form <https://fmrif.nimh.nih.gov/techs_form>`_). It’s important to fill out the information correctly (format wise), particularly the dates (spacing, abbreviation) as the program uses it to figure out when to send the email.

It should spit out a line giving you a job number and a send date/time. To check on the program type::

   atq

which will give you a list of the dates/times things will be sent or if you need to remove the email if the scan was cancelled::

   atrm THEJOBNUMBER

get the job number from atq The atq list is specific to helix or felix, so remember which one you used (or always use the same one).
