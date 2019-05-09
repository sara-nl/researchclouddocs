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

The workspaces in Research Cloud are volatile, this means any data stored on the workspace itself will be gone when a workspace is stopped. As persistent storage every Collaeborative Organisation (CO) in research cloud receives a storage space in ResearchDrive. To connect the rseaerchdrive to the workspaces based on the users own identity researchdrive needs to be linked to every CO in the research cloud portal. The link is created in two steps. First the accountname and a webDAV token from your researchdrive account need to be linked to your Research Cloud profile. Go to the profile page, and use the 'link' button of the researchdrive quick action card. You are then asked for your ResearchDrive accountname and WebDAV token which you can get with the following steps in the ResearchDrive user interface:


- Go to your name on the right of the screen and click Settings
- In the menu on the left, choose Security
- Scroll to WebDAV passwords and click on Create new app password
- The name of the WebDAV password can be chosen by the user, but a good example would be RSC, so you know what you linked using this WebDAV token.
- After generation the accountname and token can be copiedd to the form in thee research cloud portal

After the token is added to your research Cloud profile it has to be shared with the COs you want to use the researchDrive storage with. This can be done by clicking 'ResearchDrive token not linked, click here to link' in the CO card.


