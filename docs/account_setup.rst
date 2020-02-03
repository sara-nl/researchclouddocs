Setting up your account
======================================

After you have an active account in ResearchCloud some information needs to be linked to be able to use all features. 


.. _label-totp:

TOTP 
--------------

Web applications usually are protected by username + password. In order for us not to have to pre-generate any passwords, we set up most of the applications offered in the ResearchCloud catalog to work with 
`Time-based One-time Password authentication <https://en.wikipedia.org/wiki/Time-based_One-time_Password_algorithm>`_, or TOTP.

.. note::

    When a TOTP-enabled workspace asks for a password, you will type a numeric code generated in an app on your mobile phone. 


TOTP per Collaborative Organisation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Each Collaborative Organisation requires its own entry in your TOTP app. When logging into a workspace, you must therefore know which CO the workspace belongs to.

The first thing you need is a TOTP app for your phone.
If you already use TOTP authentication, you can use that app for Research Cloud as well.

Otherwise, you need to install a TOTP app, several good apps are available. 
Here is a small selection, you can find those apps in your usual mobile phone's app store:

- Google Authenticator
- `FreeOTP Authenticator`_ (by RedHat)
- Authy_

.. _FreeOTP Authenticator: https://freeotp.github.io/
.. _Authy: https://authy.com/download/

A separate TOTP entry has to be set up for each of your :doc:`Collaborative Organisation (CO) </collaborative_organisations>` 
and one more for your private (i.e.: non-CO-related workspaces). 
You do this by scanning a QR code with the TOTP app on your mobile phone. 

- go to the "Profile" page and look at your personal profile and each CO.
- first time: you see a message "Time based password not set, click to set"
- reset: open the context menu (three vertical dots) and use "Reset Time based password"
- follow the instructions
- test access with a workspace, if you have one for that CO.

.. warning::

    The QR code and the entries in your TOTP app should be considered **secrets**.
    Make sure nobody can copy your QR code from your screen during set-up.
    Protect access to your phone (and the TOTP app).

We can only display a QR code once, but you can always reset a TOTP entry. 
This replaces (invalidates) the old entry. Repeat this for all entries in case of a lost phone.

The TOTP app on your phone may show multiple entries. 
Each of these entries includes your **username** for that CO along with a **numerical code** which you can use as a password. 
The numerical code is only valid for a short time.
If the code is about to expire, just wait to see it change and use the new one to log in.


Research Drive 
------------------

Workspaces in Research Cloud are volatile: after they cease to exist, they leave nothing behind. This applies to their data as well: any data stored on the workspace itself would be gone when a workspace is gone. In order to allow persistent storage that will outlive workspaces, every Collaborative Organisation (CO) in Research Cloud is entitled to storage space in Research Drive. 

On the other hand, Research Drive requires personal user accounts to access it. This means that, in order to access your CO's Research Drive storage from Research Cloud's workspaces you log into, Research Cloud will need to know your Research Drive's identity. In the Research Cloud portal, you can establish this link in two steps: first, you must make your Research Drive space be known to Research Cloud; second (and final) you must enable (any of) your CO's to reach your Research Drive space. 

Personal Research Drive identity link
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

In order to allow Research Cloud to know your Research Drive identity, you must know your Research Drive username and WebDAV token. You can get this by following the next steps:

- Open the Research Drive portal in a new browser tab or window: https://researchdrive.surfsara.nl.
- In the Research Drive portal, go to your name on the right of the screen and click *Settings*
- From the menu on the left, choose *Security*
- Scroll to the *WebDAV passwords* section.
- You must then type an *App name* in the text box, that will help you identify which external apps (external to Research Drive, that is) have access to your Research Drive. A good example now would be ``Research Cloud``. 
- Click on the *Create new app password* button. 
- Leave this window open while you prepare your Research Cloud portal to receive the information.

Now, let us prepare the Research Cloud portal to receive the Research Drive information:

- In a different browser window, navigate to the Research Cloud Portal.
- Go to the *Profile* page from the top menu. You will see there that there is a *Quick Action* card with the title *Research Drive*. 
- Click on the *Access* button from the *Research Drive* *Quick Action* card. 

You are then asked for your Research Drive username and WebDAV token. 

- Copy and paste now both the **username** and the **WebDAV token** from the Research Drive window to the Research Cloud window.
- Submit the form. 

If you now click on the *Research Drive* *Quick Action* card's *Access* button, a new browser window will open with your Research Drive displayed. This is a sign that it all went well.

Research Drive identity for CO's
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

After you have linked your Research Drive identity to your Research Cloud profile, you can link it with your CO's. You can do this so:

- In the Research Cloud portal, to go your Profile page. Under the heading *Collaborative organisations* you can see one card for each of the CO's you are a member of.
- For each CO you want to access Research Drive from, you must click the button *Drive not linked, click to link* in the corresponding CO card.


