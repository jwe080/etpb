.. _GettingStarted:


Getting Started
===============


Welcome to the lab! 


Here are some things you'll need to do to get started:

.. [[Training Check list (coming soon)]]

Imaging
-------

* subscribe to etpb-imaging list at: `list.nih.gov <http://list.nih.gov>`_

  * login, search for etpb-imaging, subscribe

* sign up for:
 
  * basic MRI `safety training <http://intranet.nmrf.nih.gov/safety_training.htm>`_

    * 7T safety training (email Kenny after the following two items are complete)

    * universal precautions
  * CPR

* get an `NMRF DICOM account <https://foley.nmrf.nih.gov/accounts/seleAcctType.php>`_
* get `access to the NMRF center <http://intranet.nmrf.nih.gov/centeraccess.html>`_

Other useful links to the main imaging centers:

`FMRIF <https://fmrif.nimh.nih.gov/internal/docs>`_
`NMRF <http://intranet.nmrf.nih.gov/>`_


Computer Stuff
--------------

HPC account setup
^^^^^^^^^^^^^^^^^

* get an NIH High-Performance Computing (HPC) account.  This does requrie an NIH account - you have one if you have an @nih.gov email.
  * Request one `here <https://hpc.nih.gov/nih/accounts/account_request.php>`_

* `setup <https://hpc.nih.gov/docs/connect.html>`_ NoMachine `(NX) <https://www.nomachine.com/download>`_ client on your computer
  * look under persistent connections NX


Further account setup instructions:

* start NX
* open your your .bashrc file for editing
   * open a terminal `more details here <https://access.redhat.com/documentation/en-US/Red_Hat_Enterprise_Linux/4/html/Step_by_Step_Guide/s1-starting-xterm.html>`_
     * type
.. code-block:: console

          gedit ~/.bashrc

* add the following lines to the end of the file
.. code-block:: bash

   # Source ETPB definitions
   if [ -f /data/MoodGroup/code/IRTA_setup/etpb_bashrc.sh ]; then
        source /data/MoodGroup/code/IRTA_setup/etpb_bashrc.sh
   fi

save the file, terminate the NX session, log back in and you're all set!

Helpful Links
-------------

* `HPC training links <https://hpc.nih.gov/training/>`_, lots of stuff here but specifically:

  * `bash scripting <https://hpc.nih.gov/training/handouts/BashScripting-15May2017.pdf>`_
  * `common bash commands <https://hpc.nih.gov/training/handouts/BashScripting_LinuxCommands.pdf>`_

* `NIH library online tutorials <https://nihlibrary.nih.gov/training/online-tutorials>`_, you'll find some R data wrangling youtube lectures here
* `Software carpentry <https://software-carpentry.org/lessons/previous/>`_

