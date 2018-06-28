.. RSC documentation master file, created by
   sphinx-quickstart on Mon May 28 13:24:37 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Get started with SURFsara's Research Cloud
===============================

A "get started" introduction for novice users of SURFsara's Research Cloud.

.. toctree::
   :maxdepth: 2
   :caption: Contents:

Introduction
-------------

SURFsara's Research Cloud revolves around *workspaces*.
A workspace connects data and apps for your and your collaborator's use.

The Research Cloud catalog holds public and private data and apps, maintained by research communities.
Depending on your membership, some or more of these are available for your use.

After you select data and an app from the catalog, you start a workspace.
Once the workspace is created you login to the app and work on the data.
After you are done, you export the results from the app and delete the workspace.

You can form ad-hoc groups to collaborate with fellow researchers in a workspace you or they have started.

Step 1: Login to the RSC environment
-------------------------------------

SURFsara's Research Cloud is accessible by researchers from SURF_ connected institutes.
The authentication is done by your institute, through SURFconext_.

After you click the ``Login`` button, you will be presented with the SURFconext login procedure.
You will authenticate yourself to your institute with your institute's credentials.
Next you must approve to pass some information from SURFconext to the Research Cloud.

Step 2: Start your first workspace
------------------------------------

Go to ``Workspaces`` (left navigation column).
You will see a blank list because, as you are new to the Research Cloud, 
you have no personal assets yet.

Use the plus symbol in the upper right corner to start a new workspace.
Give the workspace a name and, optionally, a description.

For this first workspace, we will not bother with attaching data.

Select the ``Jupyter Hub`` bar and it will unfold.
Check the checkbox to indicate that you want this app in your workspace.

Leave the cloud infra structure and VM size selectors as they are (hpc-cloud and small VM).

Enter a Jupyter Hub username and password, **not any of your regular passwords**

Click the ``start workspace`` button (lower right) and the new workspace will begin to build.

Step 3: Login to your workspace application
--------------------------------------------

After a while, your workspace application becomes ready.
You can monitor the state on the main Workspaces page and refresh with the circular-arrow button (top right).

Once the workspace has status ``running``, click the ``more info`` button and you will see the detailed page with an ``access`` button.

Click the ``access`` button and the web page for your application opens in your browser.
Use the username and password you entered in step 2 to gain access.

Additional support
------------------

More information and support is available: write an email to `helpdesk@surfsara.nl`_.

.. _SURF: https://surf.nl/
.. _SURFconext: https://surfconext.nl/
.. _helpdesk@surfsara.nl: mailto:helpdesk@surfsara.nl