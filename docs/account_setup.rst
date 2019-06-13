Setting up your account
======================================

After you have an active account in ResearchCloud some information needs to be linked to be able to use the all the features. 


.. _label-totp:

Time-based One-time Password
-------------------------------------

Several web applications are protected by username/password authentication and we set up our apps to work with 
`Time-based One-time Password authentication <https://en.wikipedia.org/wiki/Time-based_One-time_Password_algorithm>`_, or TOTP.

When an application login page asks for a password, you will need to copy a TOTP code from an app on your phone.
This TOTP code is relative to the CO that started the workspace: each CO has its own entry in your TOTP app.

The first thing you need is a TOTP app for your phone.
If you already use TOTP authentication, you can use that app for Research Cloud as well.

Otherwise, you need to install a TOTP app, several good apps are available. 
Here is a small selection, you can find those apps in your usual mobile phone's app store:

- Google Authenticator
- FreeOTP Authenticator
- Authy

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


Link personal ResearchDrive token
-----------------------------------

The workspaces in Research Cloud are volatile, this means any data stored on the workspace itself will be gone when a workspace is stopped. As persistent storage every Collaeborative Organisation (CO) in research cloud receives a storage space in ResearchDrive. To connect the rseaerchdrive to the workspaces based on the users own identity researchdrive needs to be linked to every CO in the research cloud portal. The link is created in two steps. First the accountname and a webDAV token from your researchdrive account need to be linked to your Research Cloud profile. Go to the profile page, and use the 'link' button of the researchdrive quick action card. You are then asked for your ResearchDrive accountname and WebDAV token which you can get with the following steps in the ResearchDrive user interface:


- Go to your name on the right of the screen and click Settings
- In the menu on the left, choose Security
- Scroll to WebDAV passwords and click on Create new app password
- The name of the WebDAV password can be chosen by the user, but a good example would be RSC, so you know what you linked using this WebDAV token.
- After generation the accountname and token can be copiedd to the form in thee research cloud portal

After the token is added to your research Cloud profile it has to be shared with the COs you want to use the researchDrive storage with. This can be done by clicking 'Drive not linked, click to link' in the CO card.


