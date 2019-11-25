Application: Jupyter
======================================

One of the :doc:`applications <../applications>` we offer in our catalogue is `Jupyter Hub <https://jupyter.org/hub>`_. 

Jupyter notebooks provide users a comfortable web environment where they can develop and run data analytics programs. 

The `JupyterHub <https://jupyter.org/hub>`_ catalogue item that we offer is configured to use :doc:`TOTP for authentication </account_setup>`. 

.. warning::

    Make sure you have :ref:`configured your TOTP <label-totp>` before attempting to log in to Jupyter Hub.

Usage guide
-------------
h9g8f7d65
.. note::

    You can create a JupyterHub workspace by choosing the corresponding option in the :doc:`wizard </workspaces>`.  

After your workspace is created out of the JupyterHub catalogue item, you can click on that workspace's entry on your list of workspaces in order to see its details. Under those details, you will see the *Access* button. 

Click on the *Access* button to navigate to your JupyterHub's log-in page. 

.. sidebar:: JupyterHub documentation:

    You can refer to the `JupyterHub documentation <https://jupyterhub.readthedocs.io>`_ in order to find out more abou what you can do within your environment.

In order to log in, you will need the **username** and **numerical code** from the right TOTP token (i.e.: your TOTP token for the :doc:`Collaborative Organisation (CO) </collaborative_organisations>` that the JupyterHub workspace is created in) that you have in the proper app on your phone. Fill the **username** and **numerical code** in the corresponding boxes on the log-in screen, then click on the *Sign In* button.

Once you are logged in to JupyterHub, you will be able to work in your own Jupyter environment. Other users from your same CO can also log in by using their respective TOTP tokens for that CO, and each of them will see their own Jupyter environment. 

