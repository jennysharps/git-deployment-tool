Git auto-deployment script
based on Based on https://gist.github.com/1809044

/******************************************************************
This file should be included in the repo's root.  
You must also install git on your server and create SSH keys with no password.

More detailed steps can be found at https://gist.github.com/1809044

___________________________________________________________________

GitHub instructions
Add the SSH key to your user
1. https://github.com/settings/ssh
2. Create a new key
3. Paste the deploy key you generated on the server

Set up service hook
1. https://github.com/oodavid/server.com/admin/hooks
2. Select the Post-Receive URL service hook
3. Enter the URL to your deployment script - http://server.com/deploy.php
4. Click Update Settings

******************************************************************/
