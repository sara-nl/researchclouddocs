Setting up your account
======================================

After you have an active account in ResearchCloud ssome information needs to be linked to be able to use the all the features. 


Setup Time-based One-time Password (TEST PHASE DESCRIPTION)
-------------------------------------

For entering a web application with bassic authentication, accountname / password combination, we uses Time-based One-time Password as an extra security measure. https://en.wikipedia.org/wiki/Time-based_One-time_Password_algorithm

The TOTP has to be set up for every CO you are a member of. For the link you have to scan a QR code with a TOTP client, for example FreeOTP or Google Authenticator on a mobile phone.

Note that the QR code and the TOTP URL should be considered secrets. They cannot be reproduced and should not be stored anywhere. However, you can always re-initialize the TOTP. This will invalidate the previously initialized code and gives you the opportunity to configure a new client.

The linking of the TOTP cannot be done in the research cloud portal yet. The workaround for the setup is here: https://TOTP.rsc-surfsara.surf-hosted.nl You will be asked to login using the same authentication flow is with the research cloud portal.

Afterr linking the TOTP you can test it be logging into for example R-Studio. The TOTP app on your phone shows your login name, the, periodical changing, numerical code can be used as password. 


Link personal ResearchDrive token
-----------------------------------

.. TODOcument: describe how to link ResearchDrive token

