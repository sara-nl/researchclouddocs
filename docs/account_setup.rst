Setting up your account
======================================

After you have an active account in ResearchCloud some information needs to be linked to be able to use the all the features. 


.. _label-totp:

Time-based One-time Password
-------------------------------------

.. note:: TOTP linking cannot be fully fulfilled in the ResearchCloud portal yet. We are working on it, but the workaround for the time being is to request your QR code here: https://TOTP.rsc-surfsara.surf-hosted.nl. You will be asked to log in using the same authentication flow as with the ResearchCloud portal, and you will be able to request your QR codes.

For entering a web application with basic authentication (i.e.: a combination of a username and password) we set up our apps to work with `Time-based One-time Password authentication <https://en.wikipedia.org/wiki/Time-based_One-time_Password_algorithm>`_ as an extra security measure.  

TOTP has to be set up for every :doc:`Collaborative Organisation (CO) </collaborative_organisations>` you are a member of, and once more for your private (i.e.: non-CO-related workspaces). It boils down to scanning a QR code with a suitable app in your mobile phone. For example FreeOTP or Google Authenticator are two alternatives we have tested successfully. You can find those apps in your usual mobile phone's app store.

.. warning::

    The QR code and your specific TOTP URL should be considered **secrets**. They **cannot** be reproduced and should **not** be stored anywhere. You can always re-initialize your TOTP. This will invalidate any previously initialized tokens and this gives you the opportunity to configure a new client as well.

After linking TOTP you can test it by logging into, for example, an R-Studio or Jupyter that you may have created as a workspace. 

The TOTP app on your phone shows (possibly multiple) **active tokens**. Each of these tokens includes your **username** for that token along with a **numerical code** which you can use as a password. This code is only valid for a limited (short) time, and you can actually see it change if you keep looking at the token for a while. 


Link personal ResearchDrive token
-----------------------------------

The workspaces in Research Cloud are volatile, this means any data stored on the workspace itself will be gone when a workspace is stopped. As persistent storage every Collaeborative Organisation (CO) in research cloud receives a storage space in ResearchDrive. To connect the rseaerchdrive to the workspaces based on the users own identity researchdrive needs to be linked to every CO in the research cloud portal. The link is created in two steps. First the accountname and a webDAV token from your researchdrive account need to be linked to your Research Cloud profile. Go to the profile page, and use the 'link' button of the researchdrive quick action card. You are then asked for your ResearchDrive accountname and WebDAV token which you can get with the following steps in the ResearchDrive user interface:


- Go to your name on the right of the screen and click Settings
- In the menu on the left, choose Security
- Scroll to WebDAV passwords and click on Create new app password
- The name of the WebDAV password can be chosen by the user, but a good example would be RSC, so you know what you linked using this WebDAV token.
- After generation the accountname and token can be copiedd to the form in thee research cloud portal

After the token is added to your research Cloud profile it has to be shared with the COs you want to use the researchDrive storage with. This can be done by clicking 'Drive not linked, click to link' in the CO card.


