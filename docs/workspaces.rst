Workspaces
======================================

Workspaces are running environments where you can execute :doc:`applications <applications>` and connect to :doc:`datasets <datasets>` in Research Cloud. 


Creating workspaces
--------------------

You can simply make workspaces by following a wizard. The following pages explain each of the wizard's steps more in detail:

.. toctree::
   :maxdepth: 1
   :titlesonly:

   wizard/cos
   wizard/apps
   wizard/datasets
   wizard/size
   wizard/solution
   wizard/name

Listing workspaces
--------------------

Within the *Dashboard* section of the Research Cloud portal, you can see a list with all your workspaces. You can see their: 

* name
* timeline (related to the expiration date given to the workspace when it was created)
* state

You can click on the pencil to edit the name. 

The timeline will become red when the expiration date given to the workspace is in the past. 

The state will be *running* when all is going well with the workspace from Research Cloud's perspective. 

If you click on the down-arrow for the workspace, then you will reveal the *Workspace Details* and the *Application Details*.

Workspace's extended information
---------------------------------

In your *Dashboard*, when you click on the down-arrow next to a workspace on your list, you will display extended information. In particular, you will see:

* *Workspace Details*
* *Application Details*
* a *Delete* button

Workspace Details
^^^^^^^^^^^^^^^^^^

The *Workspace Details* for a given workspace include:

* The owner
* The Collaborative Organisation (or lack thereof)
* Date created
* Cost so far (in credits)
* Expiration date (i.e.: *Will be removed*)
* Projected total cost (in credits)

You can edit the expiration date in this section by clicking on the pencil icon adjacent to the field.

Application Details
^^^^^^^^^^^^^^^^^^^^

Depending on the :doc:`application(s) <applications>` requested for the workspace, different options will appear on this section. Typical information you can find here include:

* a list of names of applications and datasets included in the workspace
* which underlying infrastructure the workspace is running on
* IP addresses
* usernames, passwords or other log-in information for the application

Login to a workspace application
^^^^^^^^^^^^^^^^^^^^^

When the workspace has completed its initialization and is in state "running", 
you can login to the workspace application with the *Access* button at the bottom of the extended information.

This opens a new page in your browser which shows you the application's login page (depending on the application).

Most applications will ask for a username and password and you will need a TOTP code from an app on your phone.
See `TOTPsetup`_ below how to sat that up.

.. _TOTPsetup: account_setup.html#time-based-one-time-password

The username is relative to the CO used to start up the workspace (shown in the workspace details).
If you forgot the corresponding username, go to the profile page, 
find the corresponding CO (or your personal information if the workspace has no CO) and note its username.

The password is a 6-digit code shown in your phone's TOTP application.
Open your phone's TOTP app, find the right entry (if you have more than one): 
it should be labelled "SURF Research Cloud" and also show the CO name and the login.

Note: the TOTP code changes every 30 seconds and the app shows how long the code is still valid. 
Find out how long it takes you to type the code on your computer and hit the login button.
If the code is about to expire, you may decide to wait for the changing of the code.


Deleting a workspace
^^^^^^^^^^^^^^^^^^^^^

Once you are ready to delete your workspace, you can click on the *Delete* button at the bottom of the workspace's extended information. A pop-up dialogue will ask for confirmation. If you submit your confirmation then all resources claimed by the workspace will be permanently released.
