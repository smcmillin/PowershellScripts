# PowershellScripts

Since all of these are fairly short in length, I'm going to keep them in one repo.

## 30dayinactive

### O365 Powershell Script

This is the script I use at work to see if a user account has fallen through the cracks and didn't get blocked when a staff member has been offboarded. It doesn't take any action against the user account, it just exports their email to a csv for review. That csv could easily be imported into another script for automated blocking.

I used this script to help clean up my org's user accounts. We went from 300 active user accounts down to 150. 

## fulladdtodgroup

### O365 Powershell Script

The real name of this script should be "Full contact add to dgroup" or something similar. One of my frequent tasks is adding external contacts to a distribution list, but the whole workflow usually involves creating the contact first, but not always. This script does the whole workflow that I would normally do in the O365 portal: check if contact exists; if not: create, then check if they are already on the distribution list; if not: add.

This script has probably saved me at least hours after adding up all the time I'm not clicking around the admin portal.

## resetpassword

### O365 Powershell Script

I figured I should put this here because I took the time to write it. Sure, reset password scripts are the basic of basics, but this has saved me COUNTLESS clicks. Maybe it will be useful to someone, somewhere.

## SharepointPermissions

### O365 Powershell Script

This one should be functional but I haven't had an opportunity to test it yet. Essentially this takes a Sharepoint list and assigns permissions to individual items from a csv. If you have a lot of items and employees are not allowed to see all of them, it would be a massive pain to manage permissions one at a time in the browser. This lets you automate it. Well, someone has to build the csv.
