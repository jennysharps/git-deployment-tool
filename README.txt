Git auto-deployment script
Based on https://gist.github.com/1809044

/******************************************************************

___________________________________________________________________

This file should be included in the repo's root.  
You must also install git on your server and create SSH keys with no password.

More detailed steps can be found at https://gist.github.com/1809044

___________________________________________________________________

GitHub instructions
Add the SSH key to your user
1. https://github.com/settings/ssh
2. Create a new key
3. Paste the deploy key you generated on the server

Set up service hook: https://help.github.com/articles/post-receive-hooks
1. Open your repo on GitHub and go to its settings page
2. Click "Service Hooks"
3. Click "WebHook URLs"
4. Enter your URL and click "Update Settings" (the url should point to the git_deploy.php file)

******************************************************************/
